---
title: "Deployment"
---

# Deployment Guide

## Docker

```bash
docker build -f src/main/docker/Dockerfile.jvm -t inventory-service .
docker run -p 8080:8080 inventory-service
```

## Kubernetes with Helm

```bash
helm install inventory ./helm/inventory   --set image.tag=1.0.0
```

## GitHub Actions (CI/CD)

```yaml
- name: Build Quarkus
  run: ./mvnw package -DskipTests
- name: Docker Build
  run: docker build -t acme/inventory-service .
```
