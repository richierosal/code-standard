# Java Standards

## Language

- Java

## Framework

Preferred:

- Spring Boot

## Architecture

Required:

- Clean Architecture
- Layered Architecture

## Project Structure

src/main/java/
└── app/
    ├── domain/
    ├── application/
    ├── infrastructure/
    └── interfaces/

## API

Required:

- OpenAPI / Swagger
- DTO Validation
- Consistent Error Response

## Validation

Preferred:

- Jakarta Bean Validation

## Database

Preferred:

- PostgreSQL

Persistence:

- Spring Data JPA
- JOOQ

## Testing

Required:

- Unit Test
- Integration Test

Preferred:

- JUnit
- Mockito
- Testcontainers

## Rules

- Keep controllers thin
- Business logic belongs in application/domain layer
- Use dependency injection
- Avoid framework dependency in domain layer
- Validate all inputs
- Use structured logging

## Definition Of Done

- API implemented
- Validation implemented
- Tests added
- Error handling implemented
- Logging implemented