# Hey, I'm Hithesh 👋

Backend engineer building production systems from first principles. I write code to understand how systems actually work: token rotation, concurrent connection state, message durability, schema migrations. No SDK gluing. No shortcuts.

Finalizing BCA at East Point College, Bengaluru.

---

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776ab?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=websocket&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-red?style=flat-square)
![Celery](https://img.shields.io/badge/Celery-37B24D?style=flat-square&logo=celery&logoColor=white)

---

## Projects

### 🔗 Connect — Real-time Messaging Backend

**Live:** https://snazzy-begonia-cbabf5.netlify.app | **Repo:** https://github.com/hithuyeager/connect-with-friends

Production-grade real-time chat backend built solo to understand every layer of authentication and real-time systems.

**Architecture highlights:**
- JWT refresh token rotation with theft detection. Single-use tokens that invalidate the entire session chain if replayed.
- Native WebSocket real-time chat with deterministic room IDs, connection state management, live message delivery.
- Persisted message history in PostgreSQL. Every message durably written on send; offline users see full history on login.
- Google OAuth2 integration with account linking via Authlib. No auth-as-a-service SDKs.
- Async background tasks via Celery and Redis for email delivery, decoupled from the request/response cycle.
- Layered architecture: routes never touch the database; services never know about HTTP; repositories isolated from business logic.
- 9 tracked schema migrations reflecting real iterative changes, not a single upfront "perfect" schema.

**Stack:**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37B24D?style=flat-square&logo=celery&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Alembic](https://img.shields.io/badge/Alembic-FCC624?style=flat-square)

---

## Current Focus

**12-month trajectory:** Backend mastery → LLM API integration → ML/AI engineering

Diving into:
- 🗄️ PostgreSQL internals: query planning, indexes, transaction isolation
- ⚡ Async I/O and concurrency: event loops, connection pooling, backpressure
- 📈 Scaling patterns: horizontal scaling, database sharding, distributed tracing
- 🤖 LLM API design: building backends that integrate Claude/OpenAI efficiently
- 🛡️ System design: reliability, failure modes, observability

No bootcamp shortcuts. No paid certificates. Just shipping and learning the hard parts.

---

## Let's Connect

| | |
|---|---|
| 📧 **Email** | hitheshrhithu41@gmail.com |
| 💼 **LinkedIn** | www.linkedin.com/in/hithesh-r-hithu-851652328|
| 📄 **Resume** | working on it |

---

### Stats

- 20 years old, Bengaluru-based
- 50+ GitHub repositories (DSA, full-stack, systems work)
- GitHub traffic: sustained multi-visitor interest in architecture-specific code
- Target: High-paying backend role
