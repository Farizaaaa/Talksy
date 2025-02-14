# Talksy
Talksy is a fast and secure chat application built using Flutter and Firebase, offering seamless real-time messaging with a modern and intuitive interface


## Roles and Interactions Flowchart

This flowchart demonstrates the key roles (User, Seller, and Admin) and their interactions within platform.
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
User_1_1 --> message_1
User_1_2 --> message_1
User_1_3 --> message_1
message_1 --> message_2
message_1 --> message_2
message_1 --> message_2

    style FIRESTORE fill:#00FFFF,stroke:#333,stroke-width:20px,font-size:18px,padding:10px,color:#000000
    style USERS fill:#EEFFFF,stroke:#333,stroke-width:10px,font-size:18px,padding:10px,color:#000000
    style CHAT_ROOMS fill:#EEFFFF,stroke:#333,stroke-width:10px,font-size:18px,padding:10px,color:#000000
```
