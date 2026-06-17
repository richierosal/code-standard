# Flutter Standards

## Language

- Dart

## Architecture

Required:

- Clean Architecture
- MVVM or Feature-Based Architecture

## State Management

Preferred:

- Riverpod

Alternative:

- Bloc
- Cubit

## Dependency Injection

Preferred:

- Riverpod Provider
- GetIt
- Injectable

## Project Structure

lib/
├── features/
├── shared/
├── core/
└── app/

Feature structure:

features/
└── feature_name/
    ├── presentation/
    ├── domain/
    └── data/

## Networking

Preferred:

- Dio

## Local Storage

Preferred:

- Hive
- Isar
- SQLite

## Secure Storage

Required:

- flutter_secure_storage

## Testing

Required:

- Unit Test
- Widget Test
- Integration Test

## Rules

- UI must not call API directly
- Business logic belongs in use cases
- Repositories abstract data sources
- State must be predictable
- Avoid fat widgets

## Definition Of Done

- UI implemented
- API integrated
- State handled
- Error state implemented
- Loading state implemented
- Unit tests added
- Widget tests added