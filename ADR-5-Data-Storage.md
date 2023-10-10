# ADR 5: Data Storage

## Decision

Our data management strategy involves employing PostgreSQL as a relational database for structured data storage. Amazon S3 will handle cloud-based storage for user-generated content, and Redis will serve as an in-memory cache for improved data access.

## Rationale

This blend of technologies offers the speed and reliability of PostgreSQL, scalability and security of Amazon S3, and the enhanced data retrieval capabilities provided by Redis, aligning with the project's demands.

## Status

Decision put forth.

## Consequences

- Efficient data retrieval
- Scalable storage infrastructure
- Enhanced data security protocols required.
