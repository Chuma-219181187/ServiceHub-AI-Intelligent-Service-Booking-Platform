# Use Case Diagram – ServiceHub AI

```mermaid
flowchart LR

Customer((Customer))
Provider((Service Provider))
Admin((Administrator))
PaymentGateway((Payment Gateway))
NotificationService((Notification Service))
AIEngine((Recommendation Engine))

Customer --> UC1[Register/Login]
Customer --> UC2[Search Services]
Customer --> UC3[Book Service]
Customer --> UC4[Make Payment]
Customer --> UC5[Leave Review]

Provider --> UC6[Manage Services]
Provider --> UC7[Manage Bookings]

Admin --> UC8[Approve Providers]
Admin --> UC9[Manage Users]

UC3 --> UC4
UC3 --> UC10[Receive Notification]

UC4 --> PaymentGateway
UC10 --> NotificationService
UC2 --> AIEngine
```

## Explanation

The diagram illustrates how different actors interact with the ServiceHub AI system.

* **Customer** performs core actions such as searching services, booking, and reviewing.
* **Service Provider** manages services and bookings.
* **Administrator** ensures system governance and user management.
* External systems like the **Payment Gateway**, **Notification Service**, and **AI Engine** support key system operations.

Relationships:

* “Book Service” includes “Make Payment”
* Notifications are triggered after booking
* AI recommendations enhance service discovery

This directly supports stakeholder concerns such as ease of booking, reliable payments, and improved user experience.
