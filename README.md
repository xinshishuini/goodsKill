# goodsKill - AI Gateway & Microservice Platform

This project is a Java-based distributed system centered on a Spring Cloud microservice architecture, with a focus on API gateway management, authentication, AI capability integration, and high-concurrency request handling in a simulated seckill scenario.

## Project Direction

The project is designed to demonstrate the following engineering capabilities:

- Unified API gateway routing and request handling
- Service registration, discovery, and configuration management
- Authentication and access control
- AI capability integration and service abstraction
- High-concurrency traffic control and distributed system design

The primary technical focus is not only the seckill scenario itself, but also the backend engineering patterns behind it.

## Main Modules Kept for Resume / Project Showcase

The following modules are the most relevant for demonstrating backend engineering and AI integration capabilities:

- `goodskill-gateway`
  - Unified request entry
  - Route forwarding
  - Authentication and request filtering
  - Traffic management and service access control

- `goodskill-auth`
  - Login and authorization logic
  - Access control and permission validation
  - Security-related backend capability

- `goodskill-ai`
  - AI model/service integration
  - Knowledge base management
  - Unified AI request handling and error management

- `goodskill-common`
  - Shared utilities
  - Unified response structures
  - Common business and infrastructure support

- `goodskill-web`
  - API-facing entry for mock seckill operations
  - Business simulation and request triggering layer

- `goodskill-order-provider`
  - Order service logic
  - Business logic separation from gateway and request layer

- `goodskill-seckill-provider`
  - Core seckill logic
  - Inventory and concurrency-sensitive operation handling

## Core Technical Stack

- Java 21
- Spring Boot 4.x
- Spring Cloud 2025.x
- Spring Cloud Gateway
- Spring AI
- Nacos
- Redis
- MySQL
- Kafka
- MongoDB
- Elasticsearch
- RabbitMQ
- MyBatis Plus
- Dubbo
- Sa-Token
- OpenTelemetry

## Resume-Friendly Project Highlights

### 1. API Gateway and Unified Access

The gateway layer serves as the centralized entry for service access and request routing. It unifies backend service exposure and helps manage access authority, request distribution, and business isolation.

### 2. Authentication and Security Design

The auth module provides backend support for access control, login logic, and permission management. This demonstrates practical experience in securing service endpoints and managing user access.

### 3. AI Capability Integration

The AI module introduces AI-based service capabilities such as model invocation, knowledge-base enhancement, and unified service-layer integration. This is a strong indicator of backend + AI engineering readiness.

### 4. High-Concurrency Backend Design

The seckill scenario highlights distributed system patterns including:
- concurrency control
- distributed locking
- cache utilization
- queue-based asynchronous processing
- request traffic handling

### 5. Engineering Structure and Extendability

The project keeps a multi-module design that is easy to extend. It demonstrates understanding of backend architecture, service decoupling, configuration management, and infrastructure integration.

## Hidden / Non-Core Modules

The following modules are kept for project completeness but are not the primary focus for resume presentation:

- monitoring/admin modules
- auxiliary demo or extended feature modules
- optional experimental integrations
- secondary business extensions not directly related to the main architecture narrative

These modules remain available in the repository for learning and experimentation, but the project story should emphasize the main line:

AI Gateway + Microservice Architecture + Security + AI Integration + High-Concurrency Business Logic

## Recommended Resume Summary

The project is a distributed backend platform built around Spring Cloud and AI service integration, with emphasis on gateway routing, authentication, and high-concurrency request handling. It demonstrates experience in microservice architecture, backend infrastructure integration, and AI-capable service design.

## Project Philosophy

This repository is not just a single seckill demo; it is a practical backend project that demonstrates real system-level concerns, including service isolation, request management, scalable architecture, and AI-based business capability integration.

