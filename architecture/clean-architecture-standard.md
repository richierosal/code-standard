# Clean Architecture Standard

## Purpose

Design systems that are maintainable, testable, and independent from frameworks.

## Core Principle

Business rules must be protected from external details.

Frameworks, databases, UI, queues, APIs, and third-party services are implementation details.

## Layers

Recommended layers:

- Domain
- Application / Use Case
- Interface Adapter / Delivery
- Infrastructure

## Dependency Rule

Dependencies must point inward.

Outer layers may depend on inner layers.

Inner layers must not depend on outer layers.

Domain must not depend on:

- Frameworks
- Database libraries
- HTTP libraries
- Messaging libraries
- External SDKs

## Business Logic Rule

Business logic belongs only in:

- Domain
- Application / Use Case

Business logic must not live in:

- Controllers
- Handlers
- Middleware
- Repository implementations
- ORM models
- Framework-specific classes

## Layer Responsibilities

### Domain

Owns:

- Entities
- Value Objects
- Domain Rules
- Domain Errors
- Repository Interfaces

### Application / Use Case

Owns:

- Use Case Orchestration
- Transaction Flow
- Business Workflow
- Input / Output Ports

### Interface Adapter / Delivery

Owns:

- HTTP Handlers
- Controllers
- Presenters
- Request / Response Mapping
- API Validation

### Infrastructure

Owns:

- Database Implementation
- External API Clients
- Message Brokers
- Framework Configuration
- Logging Implementation

## Review Checklist

- [ ] Domain is framework independent
- [ ] Business logic is not inside handlers
- [ ] Use cases orchestrate business flow
- [ ] Repository interface is owned by inner layer
- [ ] Repository implementation is in infrastructure layer
- [ ] External dependencies are isolated
- [ ] Dependency direction points inward
- [ ] Code is testable without real infrastructure

## Anti Patterns

Avoid:

- Fat Controllers
- Business Logic in Repository
- ORM Model as Domain Model
- Framework-Driven Domain
- Circular Dependencies
- Infrastructure Leaking Into Domain
  
