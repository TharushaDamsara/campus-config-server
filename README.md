# campus-config-server

Spring Cloud Config Server for CampusFlow. Centralizes and externalizes configuration for all
CampusFlow microservices, serving config from the [campus-config-repo](https://github.com/TharushaDamsara/campus-config-repo)
Git repository.

This repository is a **Git submodule** of [campus-backend-platform](https://github.com/TharushaDamsara/campus-backend-platform).

**Student:** Tharusha Damsara (241711004)
**GCP Project ID:** campusflow-eca-2026

## Technology Stack

- Java 25
- Spring Boot 3.5.3
- Spring Cloud Config Server
- Spring Cloud Netflix Eureka Client
- Spring Boot Actuator

## Setup / Getting Started

```bash
mvn clean install
mvn spring-boot:run
```

Runs on port `8888` by default. Requires the [campus-eureka-server](https://github.com/TharushaDamsara/campus-eureka-server)
to be running for service registration.
# campus-config-server
