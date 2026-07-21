# Hi, I'm Zohaib 👋

**Junior Backend Developer — Python · Django/DRF · FastAPI · PostgreSQL**
Lahore, Pakistan · open to remote

I build backend services and ship them. Most of my work is a self-contained service you can stand up with one `docker compose up` — REST APIs, async task pipelines, real-time WebSocket systems, vector search, and the NGINX/Docker layer in front of them.

### ▶ See it running

**[fragrance-api — live demo](https://fragrance-api-eight.vercel.app)** · [API docs (Swagger)](https://web-production-265e0.up.railway.app/api/docs/)

Log in with `demo` / `demopass123` — no signup needed.

A full-stack perfumery formulation app: Django + DRF + PostgreSQL backend, React/TypeScript frontend, deployed on Railway + Vercel. JWT auth, object-level permissions, throttling, OpenAPI schema, 37 backend tests, CI on every PR.

---

### 📌 Projects

| Project | What it does | Stack |
|---|---|---|
| **[fragrance-api](https://github.com/MZohaibBaig/fragrance-api)** 🟢 *live* | Recipe/batch formulation with weight-native math, JWT auth, per-user ownership, server-side AI summaries | Django · DRF · PostgreSQL · React/TS |
| **[rag-search-api](https://github.com/MZohaibBaig/rag-search-api)** | Retrieval-augmented generation: upload → chunk → embed → vector search → grounded LLM answer | FastAPI · pgvector · Groq |
| **[production-gateway](https://github.com/MZohaibBaig/production-gateway)** | NGINX reverse proxy with tiered per-IP rate limiting fronting the RAG service | NGINX · Docker Compose |
| **[Telemetry_System](https://github.com/MZohaibBaig/Telemetry_System)** | Real-time device telemetry with WebSocket live push — no polling | FastAPI · TimescaleDB · WebSockets |
| **[document-pipeline](https://github.com/MZohaibBaig/document-pipeline)** | Async document processing with background workers | FastAPI · Celery · Redis · PostgreSQL |
| **[Flask-Student-Management-API](https://github.com/MZohaibBaig/Flask-Student-Management-API)** | CRUD REST API with correct PUT/PATCH semantics, marshmallow validation, Alembic migrations | Flask · SQLAlchemy · Docker |

Each featured repo has a README covering the design decisions and the tradeoffs — including what I'd change for production.

---

### 🔧 Tech

**Languages:** Python, SQL, TypeScript
**Backend:** Django, DRF, FastAPI, Flask
**Data:** PostgreSQL, pgvector, TimescaleDB, Redis
**Infra:** Docker, docker-compose, NGINX, Celery, GitHub Actions
**Auth/Testing:** SimpleJWT, python-jose, pytest, Vitest, Playwright

---

### 📫 Reach me

- **Email:** m.zohaibbaig@ymail.com
- **LinkedIn:** https://www.linkedin.com/in/muhammad-zohaib-baig/

*Open to junior backend roles. Fastest way to judge my work: click the demo above.*
