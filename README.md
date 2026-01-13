\# JP Morgan Chase – Midas Core



This project was built as part of the \*\*JP Morgan Chase Advanced Software Engineering Virtual Experience (Forage)\*\*.



It simulates a real-world transaction processing system using Kafka, Spring Boot, JPA, and microservices.



---



\## What this system does



\- Consumes financial transactions from a Kafka topic

\- Validates users and balances

\- Persists users and transactions to an H2 database

\- Calls an external Incentive microservice for rewards

\- Updates user balances accordingly

\- Exposes a REST API to query user balances



---



\## Tech Stack



\- Java 17

\- Spring Boot 3

\- Apache Kafka

\- Spring Data JPA

\- H2 Database

\- REST APIs

\- Testcontainers \& Embedded Kafka

\- Maven



---



\## How to run



\### 1. Start the Incentive API

```bash

cd services

java -jar transaction-incentive-api.jar



