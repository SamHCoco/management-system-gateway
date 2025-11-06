# Management System - API Gateway - Spring Cloud Gateway

## Bill of Materials

### Core Framework
- **Spring Boot**: 3.4.11
- **Spring Cloud**: 2024.0.2
- **Java**: 17

### Gateway & Routing
- `spring-cloud-starter-gateway` - Reactive API Gateway with route management
- `spring-cloud-starter-netflix-eureka-client` - Service discovery and registration
- `spring-boot-starter-actuator` - Health checks and metrics monitoring

### Development & Testing
- `spring-boot-starter-test` - Integration and unit testing framework

### Server Configuration
- **Port**: 8765
- **Profile**: Default (configurable via environment)

## Route Configuration
- Routes `/employee-service/**` requests to `EMPLOYEE-SERVICE` backend

## Build & Run
```bash
mvn clean install
mvn spring-boot:run