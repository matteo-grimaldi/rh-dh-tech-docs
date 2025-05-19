---
title: "Contributing"
---

# Contributing Guide

We welcome community contributions!

## Setup

```bash
mvn clean install
mvn quarkus:dev
```

## Commit Format

We use [Conventional Commits](https://www.conventionalcommits.org/)

Examples:

```
feat(api): add PATCH endpoint for items
fix(db): correct column type for quantity
```

## Lint & Test

```bash
mvn fmt:check
mvn test
```
