# Project-H
# MERN + Python (Agent Worker)
- Frontend: Same as Track A.
- Backend: Node/Express is the API gateway & persistence layer; publish triage jobs to a queue (Redis) or HTTP to Python.
- Agent Worker (Python): FastAPI + Pydantic + (Celery/RQ optional) for async tasks. Implement LLM calls or deterministic stub. Return structured JSON back to Node.

