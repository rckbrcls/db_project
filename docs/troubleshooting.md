# Troubleshooting

## Frontend cannot reach Flask

Checks:

- Confirm `NEXT_PUBLIC_API_URL`.
- Confirm Flask is exposed through `FLASK_PORT`.
- Confirm CORS origins include the frontend URL.

## Database does not initialize

Checks:

- Confirm Postgres environment variables in `.env`.
- Confirm the `postgres` service is healthy.
- Confirm SQL scripts and data generators still match the schema.

## Docker Compose fails

Checks:

- Confirm `.env` exists.
- Confirm required ports are free.
- Confirm local Docker can build `client/Dockerfile.dev` and `server/docker/Dockerfile`.
