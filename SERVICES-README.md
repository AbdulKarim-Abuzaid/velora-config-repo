This repository contains configuration templates for a Spring Boot microservices setup.

Files added:
- eureka-service.yml   -> Eureka server config (port 8761)
- room-service.yml     -> Room service config (port 8081)
- gateway-service.yml  -> Spring Cloud Gateway config (port 8080)
- docker-compose.yml   -> Compose file to run services (expects built images)

Next steps:
1. Create Spring Boot projects for each service (Eureka server, Room service, Gateway).
2. Use these YAMLs as application.yml (or merge into your config server).
3. Build Docker images and update docker-compose or change to local builds.
