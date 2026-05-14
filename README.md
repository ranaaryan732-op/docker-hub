# Docker Hub — Portfolio CI/CD

![Build Status](https://github.com/ranaaryan732-op/docker-hub/actions/workflows/docker-build-push.yml/badge.svg)
![Docker Pulls](https://img.shields.io/docker/pulls/ranaaryan732/portfolio-site?logo=docker)

Automated Docker build and push pipeline using **GitHub Actions**.  
Every push to `main` builds the image and pushes it to Docker Hub.

## Run the container

```bash
docker run -d -p 8080:80 ranaaryan732/portfolio-site
```

Open → [http://localhost:8080](http://localhost:8080)

## Required GitHub Secrets

| Secret | Value |
|--------|-------|
| `DOCKER_USERNAME` | `ranaaryan732` |
| `DOCKER_PASSWORD` | Docker Hub access token |

Add them at: **Settings → Secrets and variables → Actions**
