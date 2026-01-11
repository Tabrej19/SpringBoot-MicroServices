# SpringBoot-MicroServices

## Table of Contents
1. [Introduction](#introduction)
2. [Architecture](#architecture)
3. [Tech Stack](#-tech-stack)
4. [Prerequisites](#prerequisites)
5. [Running Locally](#running-locally)

## Architecture
[Insert Diagram Image]
*   **Gateway:** Routes requests
*   **Service A:** Handles [X] logic
*   **Service B:** Handles [Y] logic

## 🚀 Tech Stack
*(Copy the detailed tech stack from above here)*

## Prerequisites
*   JDK 17 or higher
*   Docker & Docker Compose
*   Maven/Gradle

## Running Locally
```bash
# Run Infrastructure Components (Eureka, Config, Gateway)
docker-compose -f infra-compose.yml up -d

# Run Individual Microservices
cd service-a
mvn spring-boot:run
