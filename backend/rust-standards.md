# Rust Standards

## Language

- Rust

## Framework

Preferred:

- Axum

Alternative:

- Actix Web

## Architecture

Required:

- Layered Architecture
- Clean Architecture where appropriate

## Project Structure

src/
├── domain/
├── application/
├── infrastructure/
├── interfaces/
└── main.rs

## Error Handling

Required:

- Explicit error types
- Result-based flow
- No panic in application flow

## Database

Preferred:

- PostgreSQL

Libraries:

- SQLx
- Diesel

## API

Required:

- OpenAPI when exposed externally
- Typed request/response models

## Testing

Required:

- Unit Test
- Integration Test

## Rules

- Prefer explicit types
- Avoid unnecessary cloning
- Avoid panics
- Keep domain independent from framework
- Validate all external input

## Definition Of Done

- Code compiles
- Tests pass
- Errors handled
- API documented
- Logging implemented