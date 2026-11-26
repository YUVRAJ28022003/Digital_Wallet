# Digital_Wallet

# E-Wallet Application – Secure Digital Payment System

## Project Description

The **E-Wallet Application** is a digital payment system designed to make financial transactions simple, secure, and efficient. It enables users to manage their digital wallets, add funds, transfer money to other users, monitor account balances, and view their transaction history through a user-friendly interface. The project aims to provide a convenient cashless payment solution while ensuring data security, transaction reliability, and a smooth user experience.

The application is developed using **Java 17 and Spring Boot** for backend development, with **MySQL** as the database and **Hibernate ORM** for efficient data persistence and management. The system follows a **Microservices Architecture**, dividing the application into independent services such as User Service, Wallet Service, Transaction Service, Notification Service, and Admin Service. Each service handles a specific business functionality and communicates with other services through RESTful APIs. This modular approach improves maintainability, scalability, flexibility, and independent deployment.

A major feature of the application is its focus on security. **Spring Security, OAuth2, and JSON Web Tokens (JWT)** are used to provide secure authentication and authorization. Role-Based Access Control (RBAC) helps restrict access to sensitive operations based on user roles. The system also incorporates AES-256 encryption to protect sensitive information, transaction monitoring to identify suspicious activities, and audit logs to maintain records of transactions and authentication attempts.

To support efficient communication between services, **Apache Kafka** is used for asynchronous messaging, particularly for notification-related operations. Hibernate simplifies database operations by mapping Java objects to relational database tables and supporting CRUD operations. The application also considers modern deployment practices using **Docker** for containerization and **Kubernetes** for managing, scaling, and orchestrating microservices.

The development and testing process includes unit testing with JUnit and Mockito, integration testing to validate communication between services, end-to-end testing to verify complete user workflows, and performance testing to assess system reliability under different workloads. CI/CD pipelines can automate the build, testing, and deployment process, while monitoring and logging tools help maintain application health.

Overall, the E-Wallet Application demonstrates the practical implementation of modern Java backend technologies, microservices, secure authentication, database management, and event-driven communication. It provides a foundation for a scalable and reliable digital payment platform and highlights how modern software engineering practices can be used to develop financial applications that support convenient and secure digital transactions.

## Technologies Used

- **Programming Language:** Java 17
- **Backend Framework:** Spring Boot, Spring Security
- **Database:** MySQL
- **ORM:** Hibernate
- **Authentication:** OAuth2, JWT
- **Messaging:** Apache Kafka
- **Architecture:** Microservices, REST APIs
- **Deployment:** Docker, Kubernetes
- **Testing:** JUnit, Mockito
