# reporting-service

Generates analytics reports

## Getting started
```bash
docker build -t reporting-service .
docker run -p 8080:8080 reporting-service
```

## CI/CD

This repo has a GitHub Actions pipeline that builds and smoke-tests
the Docker image on every push to main.

---
*Provisioned by [IDP Platform](https://github.com/aftabkh4n/idp-platform)*