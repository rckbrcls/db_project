# Deployment

## Overview

This archived academic project includes Dockerfiles and `docker-compose.yml`. Treat the setup as historical until verified.

## Components

- `docker-compose.yml`: local orchestration.
- `client/Dockerfile`: frontend container.
- `server/docker/Dockerfile`: backend container.

## Environment Variables

See `.env.example` for database and application placeholders.

## Notes

- The setup may be outdated and should be verified before reuse.
- Do not expose real database credentials in committed files.
