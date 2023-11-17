# Event-Driven Microservices with Java, Spring, Kafka, and Elasticsearch

## Overview

This project is a demonstration of a master event-driven microservices architecture, implemented using Java, Spring Boot, Spring Cloud, Kafka, and Elasticsearch. The goal is to showcase best practices and patterns for building scalable, resilient, and loosely-coupled microservices that communicate through asynchronous events.

## Technologies Used

- Java
- Spring Boot
- Spring Cloud
- Kafka
- Elasticsearch

## Features

- Externalized configuration with Spring Cloud Config
- CQRS with Kafka and Elastic search
- Api versioning for versioning of Rest APIs
- Service Registration and Discovery with Spring Cloud and Netflix Eureka
- Api Gateway with Spring Cloud Gateway
- Circuit breaker with Spring Cloud Gateway and Resilience4j
- Rate limiting with Spring Cloud Gateway and Redis to use Redis as the Rate limiter
- Distributed tracing with SLF4J MDC, Spring Cloud Sleuth and Zipkin
- Log aggregation with ELK stack (Elasticsearch, Logstash and Kibana)
- Client side load balancing with Spring Cloud Load Balancer
- Database per Service
- Messaging between microservices using Kafka
