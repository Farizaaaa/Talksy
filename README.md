# Talksy
Talksy is a fast and secure chat application built using Flutter and Firebase, offering seamless real-time messaging with a modern and intuitive interface


## Roles and Interactions Flowchart

This flowchart demonstrates the key roles and their interactions within platform.
```mermaid
graph TD
    FIRESTORE --> CHAT_ROOMS
    FIRESTORE --> USERS
    USERS --> User_1  
    User_1 --> User_2
User_2 --> User_3
    CHAT_ROOMS --> User_1_1
CHAT_ROOMS --> User_1_2
CHAT_ROOMS --> User_1_3
User_1_1 --> message_1_1
User_1_2 --> message_1_2
User_1_3 --> message_1_3
message_1_1 --> message_1_1_1
message_1_2 --> message_1_2_1
message_1_3 --> message_1_3_1

    style FIRESTORE fill:#00FFFF,stroke:#333,stroke-width:20px,font-size:18px,padding:10px,color:#000000
    style USERS fill:#00F00F,stroke:#333,stroke-width:10px,font-size:18px,padding:10px,color:#000000
    style CHAT_ROOMS fill:#00F00F,stroke:#333,stroke-width:10px,font-size:18px,padding:10px,color:#000000
    style User_1 fill:#EEFFFF,stroke:#333,stroke-width:20px,font-size:18px,padding:10px,color:#000000
 style User_2 fill:#EEFFFF,stroke:#333,stroke-width:20px,font-size:18px,padding:10px,color:#000000
 style User_3 fill:#EEFFFF,stroke:#333,stroke-width:20px,font-size:18px,padding:10px,color:#000000
style User_1_1 fill:#EEFFFF,stroke:#333,stroke-width:20px,font-size:18px,padding:10px,color:#000000
 style User_1_2 fill:#EEFFFF,stroke:#333,stroke-width:20px,font-size:18px,padding:10px,color:#000000
 style User_1_3 fill:#EEFFFF,stroke:#333,stroke-width:20px,font-size:18px,padding:10px,color:#000000
```
