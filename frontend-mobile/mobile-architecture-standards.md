# Mobile Architecture Standards

## Principles

* SOLID
* Clean Architecture
* Separation of Concerns

## Layers

presentation/
domain/
data/

## Rules

* UI must not access data source directly
* Domain layer must be framework independent
* Dependency flows inward
* Business logic belongs in domain layer

## Offline Strategy

Preferred:

* Repository Pattern
* Local Cache
* Sync Strategy

## Security

Required:

* Secure Storage
* Token Protection
* Encrypted Communication
