# Architecture

## Overview

`db_project` is an academic full-stack system for managing sports facility reservations and activities. It combines a PostgreSQL database, Flask backend, Next.js frontend, SQL scripts, data generators, Docker Compose, and course report artifacts.

## System Components

### Database

PostgreSQL stores the modeled academic domain. SQL scripts and generator utilities live under `server/`.

### Backend

The Flask backend lives under `server/app/` and reads database, Flask, and CORS settings from environment variables.

### Frontend

The Next.js client lives under `client/` and uses `NEXT_PUBLIC_API_URL` to talk to the Flask backend.

### Docker Compose

`docker-compose.yml` wires Postgres, Flask, and Next.js together for local full-stack execution.

## Security Model

- Flask session secret comes from `FLASK_SECRET_KEY`.
- Database credentials come from environment variables.
- CORS origins are configurable through `CORS_ORIGINS`.

## Current Status

This is archived coursework. Dependencies, Docker assumptions, and setup commands should be verified before treating it as a current production template.
