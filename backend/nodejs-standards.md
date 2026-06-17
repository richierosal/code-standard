# Node.js Standards

## Language

- TypeScript

## Framework

Preferred:

- NestJS

Alternative:

- Fastify
- Express

## Architecture

Required:

- Modular Architecture
- Clean Architecture when complexity grows

## Project Structure

src/
├── modules/
├── shared/
├── infrastructure/
└── main.ts

## API

Required:

- OpenAPI / Swagger
- DTO Validation
- Consistent Error Response

## Validation

Preferred:

- Zod
- class-validator

## Database

Preferred:

- PostgreSQL

ORM:

- Prisma
- TypeORM

## Testing

Required:

- Unit Test
- Integration Test

Preferred:

- Jest
- Supertest

## Rules

- Keep controllers thin
- Business logic belongs in services/use cases
- Repositories abstract persistence
- Validate all inputs
- Use structured logging
- Never log secrets

## Definition Of Done

- API implemented
- Validation implemented
- Tests added
- Error handling implemented
- Logging implemented