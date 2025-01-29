# Microservices Project

## Services

1. **Service Company**: Handles company-related business logic.
2. **Service Config**: Centralized configuration service (Spring Cloud Config).
3. **Service Registration**: Service registry (Eureka Server).
4. **Service Proxy**: API Gateway ( Spring Cloud Gateway).

## How to Run

1. Start the `service-config`.
2. Start the `service-registration`.
3. Start the other services (`service-company` and `service-proxy`).

## Prerequisites

- Java 17+
- Maven 3.4+
- Spring Boot
