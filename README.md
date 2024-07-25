# Library Management System

Library Management System is a comprehensive application designed with a microservices architecture using Java, Spring Boot, and Spring Cloud. This project includes multiple independent services such as user management, book management, notification service, employee management, borrowing service, and a discovery server.

## Features
- User authentication and authorization
- Book information management and storage
- Notification system via email and messages
- Employee management and book borrowing/return system
- API Gateway for request routing and security
- Automatic service discovery with Eureka Server
- Distributed tracing and monitoring with Spring Cloud Sleuth and Zipkin
- Message-driven microservices communication with Spring Cloud Stream
- Containerization and orchestration with Docker & Kubernetes
- Deployment and hosting on AWS & Azure

## Technologies
- Java, Spring Boot, Spring Cloud, Spring Security, Spring Data JPA
- Thymeleaf, Bootstrap, H2 Database
- Eureka Server, API Gateway, Spring Cloud Sleuth, Zipkin, Spring Cloud Stream
- Docker, Kubernetes
- Lombok, Maven
- Git, GitHub, Jenkins
- AWS, Azure

## Project Setup
1. Clone the repository:
    ```sh
    git clone https://github.com/trthanhdo41/library-management-system.git
    ```
2. Navigate to the project directory:
    ```sh
    cd library-management-system
    ```
3. Build the project:
    ```sh
    mvn clean install
    ```
4. Run the services: Follow the instructions in each service's README file.

For more details, refer to the documentation in each service's directory.

## Project Links
- [GitHub Repository](https://github.com/trthanhdo41/library-management-system)
