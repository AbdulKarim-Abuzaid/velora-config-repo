# Velora Config Repository

Centralized configuration repository for the **Velora Microservices Platform** powered by **Spring Cloud Config Server**.

This repository contains all externalized configuration files required by Velora microservices, allowing centralized configuration management and easier maintenance across different environments.

## Overview

Velora follows a microservices architecture where each service has its own configuration requirements, such as:

- Server ports
- Database connections
- Eureka service discovery configuration
- API Gateway routes
- Security settings
- Application-specific properties

Instead of storing configurations inside each microservice, Velora uses **Spring Cloud Config** to provide a single centralized configuration source.

## Architecture

                     Git Repository
                    velora-config
                          |
                          |
                          v
              Spring Cloud Config Server
                      Port: 8888
                          |
    ------------------------------------------------
    |              |              |                |
    v              v              v                v