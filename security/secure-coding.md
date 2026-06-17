# Secure Coding Standard

## Input Validation

Required:

- Validate all external inputs
- Sanitize user supplied data

## Authentication

Required:

- Strong authentication
- Token validation
- Session expiration

## Authorization

Required:

- Role Based Access Control
- Least Privilege

## Secrets

Never:

- Hardcode secrets
- Store credentials in source code

Use:

- Secret Manager
- Vault
- Environment Variables

## Logging

Never log:

- Passwords
- Tokens
- Sensitive Personal Data

## Encryption

Required:

- TLS in transit
- Encryption at rest where applicable