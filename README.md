# Hey, I'm Hithesh 👋

**Backend engineer** | Real-time systems | Auth + scaling | Learning in public

I build **production systems** from first principles — not glued together from SDKs. I write code to understand how systems actually work: token rotation logic, concurrent connection state, message durability, schema migrations. Currently finalizing my BCA at East Point College (graduating June 2027) while shipping things people use.

---

## What I ship

### [**Connect** — Real-time Messaging Backend](https://github.com/hithuyeager/connect-with-friends)
A production-grade real-time chat backend I built solo to understand **every layer** of auth and real-time systems.

**Why it matters:**
- **JWT refresh token rotation with theft detection** — single-use tokens that invalidate the whole session chain if replayed
- **Native WebSocket real-time chat** — deterministic room IDs, connection state management, live delivery
- **Persisted message history** — every message durably written to Postgres; offline users see full history on login
- **Google OAuth2 integration** — account linking via Authlib without outsourcing auth
- **Async background tasks** — Celery + Redis for email delivery, decoupled from request/response
- **Layered architecture** → routes never touch the database; services never know about HTTP
- **9 tracked schema migrations** — real iterative changes, not a single "perfect" schema

**Tech:** FastAPI · PostgreSQL · Redis · Celery · WebSockets · Docker · Alembic  
**Deployed:** Render (API + worker) · Neon (database) · Netlify (frontend)  
**Live:** [snazzy-begonia-cbabf5.netlify.app](https://snazzy-begonia-cbabf5.netlify.app) — try demo account

---

## What I'm learning next

**12-month trajectory:** Backend mastery → LLM API integration → ML/AI engineering  

Currently diving into:
- **PostgreSQL internals** — query planning, indexes, transaction isolation levels
- **Async I/O + concurrency** — how async/await actually works, event loops, connection pooling
- **Scaling patterns** — horizontal scaling, database sharding, distributed tracing
- **LLM API design** — building backends that integrate Claude/OpenAI APIs efficiently
- **System design** — designing for reliability, failure modes, observability

No bootcamp shortcuts. No paid certs. Just shipping + learning the hard parts.

---

## By the numbers

- **19** years old, Bengaluru
- **50+ GitHub repositories** — ranging from DSA drills to full-stack projects
- **GitHub traffic:** sustained multi-visitor interest in architecture-specific code (database layers, repository patterns)
- **Target:** High-paying backend role within 8 months post-graduation; eventually founding a company

---

## Let's connect

- **Email:** hitheshrhithu41@gmail.com
- **LinkedIn:** [@hithesh](https://linkedin.com/in/your-linkedin)
- **GitHub:** [@hithuyeager](https://github.com/hithuyeager)
- **Resume:** [one-page PDF with live links](https://link-to-your-resume.pdf)

---

### A note on how I work

I believe in:
- **Understanding before building** — shipping something half-baked is slower than spending time on architecture
- **Layered code** — separation of concerns isn't religious dogma, it's practical isolation of bugs
- **Durability over shortcuts** — transactions, error handling, and migrations matter more than "done fast"
- **Learning in public** — GitHub is my notebook; code is how I think

If you're hiring for backend roles or want to collaborate, let's talk.

---

*Last updated: September 2026*
