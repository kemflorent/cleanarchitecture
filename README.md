# Clean Architecture Demo Project

Clean Architecture is a software design approach that emphasizes separation of concerns, maintainability, testability, and independence from frameworks or external technologies.
This demo app show how to implement it in Java especially in your Spring Boot project based on 
the case study of the book writing by Robert C. Martin - The Clean Architecture.

## Features

- **User Management**: Register as Customer, Builder, or Admin with JWT authentication

## Technical Stack

- **Backend**: Java 17+, Spring Boot 3.x
- **Database**: MySQL 8.x with JPA/Hibernate

## Getting Started

### Prerequisites

- JDK 17+
- Maven 3.6+
- MySQL 8.0+ (or Docker)

### Local Development

1. Clone the repository:
```bash
git clone https://github.com/yourusername/sonator.git
cd sonator
```

2. Configure application properties:
```bash
src/main/resources/application.properties
# Edit application.properties with your settings
```

3. Build and run the application:
```bash
mvn clean spring-boot:run
```

4. Access the application:
- API: http://localhost:8081/api/v1/

## API Endpoints

The API is organized into the following modules:
- `/api/v1/notifications/*` - Notification management endpoints


## License

This project is licensed under the Apache License 2.0.

