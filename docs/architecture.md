---
title: "Architecture"
---

# System Architecture

```mermaid
graph TD
  UI[Frontend App] --> API
  API[Quarkus Inventory Service] --> DB[(PostgreSQL)]
  API --> Auth[Keycloak]
  API --> Metrics[Prometheus]
```

## Modules

- **REST Layer** – Exposes endpoints for inventory manipulation
- **Persistence Layer** – JPA & Hibernate ORM with Panache
- **Security** – JWT with RBAC
- **Metrics** – Prometheus & Micrometer integration
