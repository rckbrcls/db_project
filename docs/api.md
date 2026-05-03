# API Documentation

## Overview

The backend is a Flask API under `server/app/`. Route modules are grouped by domain, including authentication and internal dashboard behavior.

## Environment

The frontend points to the backend through:

```text
NEXT_PUBLIC_API_URL
```

The Flask app uses:

- `FLASK_RUN_HOST`
- `FLASK_RUN_PORT`
- `CORS_ORIGINS`

## Notes

- Endpoint-level request/response examples were not added because route schemas were not fully audited in this pass.
- Use `server/app/routes/` as the source of truth for exact route paths.
- Keep this file updated if the coursework API is revived.
