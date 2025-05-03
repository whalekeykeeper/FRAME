# FRAME
From Incidental Vocabulary Learning to Explicit Vocabulary Learning with an Open Learner Model

## Backend
FastAPI + PostgresSQL + SQLAlchemy + Alembic

```
docker compose -f docker-compose.dev.yml up -d

python3.11 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt

uvicorn app.main:app --host 0.0.0.0 --port 8000 --reload
```

## Frontend
Vue.js 3.0

```
npm install
npm run dev
```
