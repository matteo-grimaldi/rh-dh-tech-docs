---
title: "Troubleshooting"
---

# Troubleshooting

## Common Issues

<details>
<summary>App won't start</summary>

Ensure the DB is reachable and environment variables are loaded.

</details>

<details>
<summary>JWT auth fails</summary>

Check that the token is issued by the right Keycloak realm and that the public key is configured.

</details>

## Debug Tips

- Add `?debug=true` to `/items` endpoint for verbose logs.
- Enable Quarkus dev mode: `mvn quarkus:dev`
