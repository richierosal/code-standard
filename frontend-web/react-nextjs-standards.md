# React & NextJS Standards

## Framework

Preferred:

* NextJS App Router

## Structure

src/
features/
shared/
components/
hooks/
services/

## Forms

Preferred:

* React Hook Form
* Zod

## State Management

Preferred:

* Zustand
* TanStack Query

## API Layer

Separate API Client

Do not call APIs directly from UI components.

## Performance

Required:

* Lazy Loading
* Image Optimization
* Server Components when appropriate
