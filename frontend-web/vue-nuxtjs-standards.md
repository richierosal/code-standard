# Vue & Nuxt Standards

## Framework

Preferred:

- Nuxt 3

Alternative:

- Vue 3

## Language

Preferred:

- TypeScript

## Architecture

Required:

- Feature Based Architecture

Structure:

src/
├── features/
├── shared/
├── components/
├── composables/
├── services/

Nuxt:

app/
components/
composables/
pages/
server/

## State Management

Preferred:

- Pinia

Avoid unnecessary global state.

## API Layer

Required:

- Typed API Client
- Service Layer

Never call APIs directly from UI components.

## Forms

Preferred:

- vee-validate

Validation:

- Zod
- Yup

## UI Libraries

Preferred:

- Nuxt UI
- Vuetify

Alternative:

- PrimeVue

## Composables

Required:

- Shared logic belongs in composables

Avoid duplicated business logic.

## Routing

Vue:

- Vue Router

Nuxt:

- File Based Routing

## SSR

Nuxt Preferred:

- SSR by default
- SSG when applicable

## Testing

Required:

- Unit Test
- Component Test

Preferred:

- Vitest
- Vue Test Utils

E2E:

- Playwright

## Performance

Required:

- Lazy Loading
- Code Splitting
- Image Optimization

## Accessibility

Required:

- Semantic HTML
- Keyboard Navigation
- Focus Management
- WCAG Compliance

## Rules

- Prefer Composition API
- Keep components small
- Use composables for shared logic
- Separate presentation and business logic
- Strong typing wherever possible

## Definition Of Done

- Responsive
- Accessible
- API Integrated
- Error State Implemented
- Loading State Implemented
- Empty State Implemented
- Tests Passed