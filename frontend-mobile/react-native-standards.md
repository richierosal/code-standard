# React Native Standards

## Language

- TypeScript

## Architecture

Required:

- Feature-Based Architecture
- Clean Architecture where appropriate

## Framework

Preferred:

- React Native
- Expo when suitable

## State Management

Preferred:

- Zustand
- TanStack Query

Alternative:

- Redux Toolkit

## Forms

Preferred:

- React Hook Form
- Zod

## Navigation

Preferred:

- React Navigation

## Project Structure

src/
├── features/
├── shared/
├── components/
├── hooks/
├── services/
└── navigation/

## API Layer

Required:

- Typed API Client
- Centralized Error Handling

## Storage

Preferred:

- AsyncStorage
- MMKV

Secure Storage:

- Expo SecureStore
- Keychain

## Testing

Required:

- Jest
- React Native Testing Library

E2E:

- Detox
- Maestro

## Rules

- No API calls directly inside UI components
- Separate presentation from business logic
- Keep components small
- Validate all forms with schema
- Handle loading, empty, and error states

## Definition Of Done

- Screen implemented
- API integrated
- Navigation handled
- Form validation implemented
- Error state implemented
- Tests added