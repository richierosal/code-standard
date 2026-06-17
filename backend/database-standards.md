# Database Standards

## Preferred Database

Primary:

* PostgreSQL

Secondary:

* MongoDB
* SQLite

## Rules

* Migration Required
* Index Strategy Required
* Foreign Keys Explicit
* Soft Delete When Needed

## Naming Convention

Tables:

snake_case

Columns:

snake_case

Primary Key:

id

Timestamp Fields:

created_at
updated_at

## Performance

Avoid:

* N+1 Query
* Full Table Scan

Review:

* Query Plan
* Index Usage