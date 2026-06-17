# API Standards

## API Style

Preferred:

* REST API
* OpenAPI First

## Versioning

Required:

/api/v1/
/api/v2/

## Response Format

Success:

```json
{
  "success": true,
  "data": {},
  "message": ""
}
```

Error:

```json
{
  "success": false,
  "error": {
    "code": "",
    "message": ""
  }
}
```

## Rules

* Use nouns
* Avoid verbs
* Consistent naming
* Consistent status codes

## Security

* Authentication Required
* Authorization Required
* Input Validation Required

## Observability

Required Headers:

* request_id
* correlation_id