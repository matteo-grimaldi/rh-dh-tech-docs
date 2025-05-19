---
title: "API Reference"
---

# API Reference

## Base Path

```
/api/v1/items
```

## Endpoints

| Method | Path           | Description         | Auth |
|--------|----------------|---------------------|------|
| GET    | `/items`       | List all items      | ✅   |
| GET    | `/items/{id}`  | Get item by ID      | ✅   |
| POST   | `/items`       | Create item         | ✅   |
| PUT    | `/items/{id}`  | Update item         | ✅   |
| DELETE | `/items/{id}`  | Delete item         | ✅   |

## Sample OpenAPI Snippet

```yaml
paths:
  /items:
    get:
      summary: Get all items
      responses:
        '200':
          description: OK
```

> Full OpenAPI spec available at `/q/openapi`.
