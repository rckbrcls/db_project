# Getting Started

## Requirements

- Docker Compose for the full stack.
- Node.js if running the Next.js client manually.
- Python/Flask dependencies if running the backend manually.
- PostgreSQL if not using Docker Compose.

## Environment Setup

Copy `.env.example` to `.env`:

```bash
cp .env.example .env
```

The environment file controls Postgres, Flask, Next.js, CORS, and exposed ports.

## Docker Compose

The repository defines:

```bash
docker compose up
```

Services:

- `postgres`
- `flask_app`
- `nextjs_app`

## Manual Frontend

From `client/`, the package scripts define:

```bash
npm run dev
npm run build
npm run start
npm run lint
```

## Notes

- This documentation pass did not run Docker, build, dev, or test commands.
- The project is archived coursework; setup may need verification before reuse.
