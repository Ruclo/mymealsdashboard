# MyMeals
Full-stack restaurant dashboard with a Go backend and a React + Vite frontend.

**Structure**
- `MyMeals/` Backend (Go, REST API)
- `Mymealsfe/` Frontend (React, Vite, Caddy in Docker)
- `docker-compose.yml` Local Docker stack

**Quickstart (Docker Compose)**
1. Ensure `MyMeals/.env` exists with required variables (see `MyMeals/README.md`).
2. From the repo root, run:
```bash
docker compose up --build
```
3. Backend API is at `http://localhost:8080`.
4. Frontend is served by Caddy (see `Mymealsfe/README.md` for host details).

**Run (Local)**
1. Backend: follow `MyMeals/README.md`.
2. Frontend: follow `Mymealsfe/README.md`.

**Related**
- Backend: `MyMeals/README.md`
- Frontend: `Mymealsfe/README.md`
