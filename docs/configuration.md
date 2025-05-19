---
title: "Configuration"
---

# Configuration

Configuration is managed via `application.properties` and environment variables.

## Core Properties

```properties
quarkus.datasource.jdbc.url=jdbc:postgresql://localhost/inventory
quarkus.datasource.username=postgres
quarkus.datasource.password=secret
quarkus.http.port=8080
quarkus.log.level=INFO
```

## Environment Variables

| Key                       | Default      | Description             |
|--------------------------|--------------|-------------------------|
| `DB_USER`                | `postgres`   | Database user           |
| `DB_PASSWORD`            | `secret`     | Database password       |
| `JWT_SECRET`             | (required)   | JWT signing secret      |
