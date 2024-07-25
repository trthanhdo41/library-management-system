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
- Message-driven microservices communication with Spring Cloud Stream and Kafka
- Containerization and orchestration with Docker & Kubernetes
- Deployment and hosting on AWS & Azure

## Technologies
- Java, Spring Boot, Spring Cloud, Spring Security, Spring Data JPA
- Thymeleaf, Bootstrap, H2 Database
- Eureka Server, API Gateway, Spring Cloud Sleuth, Zipkin, Spring Cloud Stream
- AxonServer, Kafka
- Docker, Kubernetes
- Lombok, Maven
- Git, GitHub, Jenkins
- AWS, Azure

## Prerequisites
- Java 11 or later
- Maven 3.6.3 or later
- Docker
- Docker Compose
- AxonServer
- Apache Kafka

## Project Setup
1. **Clone the repository:**
    ```sh
    git clone https://github.com/trthanhdo41/library-management-system.git
    ```
2. **Navigate to the project directory:**
    ```sh
    cd library-management-system
    ```

3. **Build the project:**
    ```sh
    mvn clean install
    ```

## Setting up and Running AxonServer

1. **Download AxonServer:**
    - Download AxonServer SE from [AxonIQ's website](https://download.axoniq.io/axonserver/AxonServer.zip).

2. **Extract the downloaded zip file:**
    ```sh
    unzip AxonServer.zip -d axonserver
    cd axonserver
    ```

3. **Run AxonServer:**
    ```sh
    java -jar axonserver.jar
    ```

## Setting up and Running Apache Kafka

1. **Download and Extract Kafka:**
    - Download Kafka from [Apache Kafka's website](https://kafka.apache.org/downloads).

2. **Extract the downloaded tar file:**
    ```sh
    tar -xzf kafka_2.13-2.8.0.tgz
    cd kafka_2.13-2.8.0
    ```

3. **Start Zookeeper:**
    ```sh
    bin/zookeeper-server-start.sh config/zookeeper.properties
    ```

4. **Start Kafka Server:**
    Open another terminal and run:
    ```sh
    bin/kafka-server-start.sh config/server.properties
    ```

## Running the Services

### Eureka Server (Discovery Server)
1. **Navigate to the discovery server directory:**
    ```sh
    cd discoveryserver
    ```
2. **Run the Eureka Server:**
    ```sh
    mvn spring-boot:run
    ```

### API Gateway
1. **Navigate to the API Gateway directory:**
    ```sh
    cd apigateway
    ```
2. **Run the API Gateway:**
    ```sh
    mvn spring-boot:run
    ```

### User Service
1. **Navigate to the user service directory:**
    ```sh
    cd userservice
    ```
2. **Run the User Service:**
    ```sh
    mvn spring-boot:run
    ```

### Book Service
1. **Navigate to the book service directory:**
    ```sh
    cd bookservice
    ```
2. **Run the Book Service:**
    ```sh
    mvn spring-boot:run
    ```

### Borrowing Service
1. **Navigate to the borrowing service directory:**
    ```sh
    cd borrowingservice
    ```
2. **Run the Borrowing Service:**
    ```sh
    mvn spring-boot:run
    ```

### Employee Service
1. **Navigate to the employee service directory:**
    ```sh
    cd employeeservice
    ```
2. **Run the Employee Service:**
    ```sh
    mvn spring-boot:run
    ```

### Notification Service
1. **Navigate to the notification service directory:**
    ```sh
    cd notificationservice
    ```
2. **Run the Notification Service:**
    ```sh
    mvn spring-boot:run
    ```

### Common Service
1. **Navigate to the common service directory:**
    ```sh
    cd commonservice
    ```
2. **Run the Common Service:**
    ```sh
    mvn spring-boot:run
    ```

## Project Links
- [GitHub Repository](https://github.com/trthanhdo41/library-management-system)
