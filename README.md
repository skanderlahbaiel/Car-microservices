

# Java Microservices with Spring Boot and Spring Cloud

## Description

This project demonstrates how to build a secure Java microservices architecture using Spring Boot and Spring Cloud. It leverages Spring Data REST to expose JPA repositories as RESTful APIs and utilizes Spring Security with OAuth support for authentication and authorization. The microservices architecture is orchestrated using Spring Cloud Gateway for routing and Netflix Eureka for service discovery.

## Features

- Service Discovery with Netflix Eureka
- Routing with Spring Cloud Gateway
- Security with OAuth 2.0 and OpenID Connect
- Refresh Tokens for enhanced security
- Integration with Auth0 for identity management




## Building the Services

1. Create a project directory:
   ```bash
   mkdir spring-boot-microservices && cd spring-boot-microservices
   ```

2. Generate projects using start.spring.io's REST API:
   ```bash
   # Create discovery-service
   # Create car-service
   # Create api-gateway
   ```

3. Open the directory in your IDE (e.g., IntelliJ IDEA):
   ```bash
   idea .
   ```

## Running the Applications

1. Start the Discovery Service using Eureka:
   ```bash
   cd discovery-service
   ./gradlew bootRun
   ```

2. Launch the Car Service with Spring Data REST:
   ```bash
   cd car-service
   ./gradlew bootRun
   ```

3. Run the API Gateway:
   ```bash
   cd api-gateway
   ./gradlew bootRun
   ```

## Security with Auth0

Configure your applications with Auth0 for secure authentication and authorization. Follow the provided instructions to set up Auth0 applications and configure your microservices to use the provided security features.

## Technologies Used

- Spring Boot
- Spring Cloud
- Netflix Eureka
- Spring Cloud Gateway
- OAuth 2.0 and OpenID Connect
- Auth0

## Contributing

Contributions to the project are welcome! Please follow the standard fork-and-pull request workflow to submit your changes.

