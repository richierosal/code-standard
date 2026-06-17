# Angular Standards

## Framework

Preferred:

- Angular (Latest LTS)

## Language

- TypeScript

## Architecture

Required:

- Feature Based Architecture
- Modular Architecture

Structure:

src/
├── app/
│   ├── core/
│   ├── shared/
│   ├── features/
│   └── layouts/

## State Management

Preferred:

- Signals (Angular Modern)
- RxJS

Alternative:

- NgRx

Use NgRx only for complex state requirements.

## Dependency Injection

Required

Use Angular DI Container.

Prefer constructor injection.

## API Layer

Required:

- HttpClient
- API Service Layer
- Typed Requests
- Typed Responses

Never call API directly from components.

## Forms

Preferred:

- Reactive Forms

Validation:

- Built-in Validators
- Custom Validators

## UI Libraries

Preferred:

- Angular Material

Alternative:

- PrimeNG

## Routing

Required:

- Lazy Loading
- Route Guards

## Testing

Required:

- Unit Test
- Component Test

Preferred:

- Jasmine
- Karma

Alternative:

- Jest

## Performance

Required:

- Lazy Loading
- Standalone Components
- OnPush Change Detection

Avoid unnecessary re-renders.

## Accessibility

Required:

- Semantic HTML
- Keyboard Navigation
- Focus Management
- WCAG Compliance

## Rules

- Smart Components should be minimal
- Business Logic belongs in Services
- Components should be reusable
- Use strongly typed interfaces
- Avoid duplicated state

## Definition Of Done

- Responsive
- Accessible
- API Integrated
- Error State Implemented
- Loading State Implemented
- Tests Passed