
raw
Sunrise api readme · MD
# Sunrise API
 
Shared backend services for the Sunrise Atelier platform — authentication, contributor management, project tracking, and the API layer powering all four programs.
 
---
 
## What it does
 
- Authentication and session management across Sunrise Atelier products
- Contributor profiles and role management
- Shared data services consumed by Neighbor, Aperture, Almanac, and Plug & Play
- Internal project and milestone tracking
## Tech stack
 
- **Runtime** — Python 3.14+
- **Framework** — FastAPI
- **Database** — PostgreSQL via SQLAlchemy + Alembic
- **Package management** — Poetry
## Getting started
 
### Prerequisites
 
- Python 3.14+
- PostgreSQL
- Poetry
### Install
 
```bash
git clone https://github.com/sunrise-atelier/sunrise-api
cd sunrise-api
poetry install
```
 
### Environment variables
 
```bash
cp .env.example .env
# fill in your database URL and secret key
```
 
### Run locally
 
```bash
poetry run uvicorn app.main:app --reload
```
 
API runs at [http://localhost:8000](http://localhost:8000). Docs at [http://localhost:8000/docs](http://localhost:8000/docs).
 
### Run migrations
 
```bash
poetry run alembic upgrade head
```
 
## Contributing
 
See [CONTRIBUTING.md](./CONTRIBUTING.md) for guidelines. Browse [`good first issue`](../../issues?q=is%3Aopen+label%3A%22good+first+issue%22) to find a starting point.
 
---
 
Part of [Sunrise Atelier](https://github.com/sunrise-atelier) — free, open-source tools for underserved communities.
