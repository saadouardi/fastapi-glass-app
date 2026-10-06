# FastAPI Glass App

A full-stack image-gallery application built with **React** and **FastAPI**.

The project was created to strengthen my understanding of Python backend architecture, API validation, relational persistence, frontend/backend integration, and automated API testing.

## Tech stack

**Frontend**
- React
- Vite

**Backend**
- Python
- FastAPI
- Uvicorn
- SQLite

**Testing & API tools**
- Pytest
- Swagger / OpenAPI

## Features

- Browse and view image data
- Search image content
- FastAPI REST endpoints
- SQLite persistence
- Frontend/backend separation
- API documentation through Swagger UI
- Backend tests with Pytest

## Project structure

```text
fastapi-glass-app/
├── frontend/
├── backend/
├── docs/
├── image_data.db
└── README.md
```

## Local setup

### Frontend

```bash
cd frontend
npm install
npm run dev
```

### Backend

Python 3.10+ is recommended.

```bash
cd backend
python -m venv .venv
```

Activate the environment, install the project dependencies, then start the API:

```bash
uvicorn main:app --host 0.0.0.0 --port 9000 --reload
```

Swagger UI is available at:

```text
http://127.0.0.1:9000/docs
```

## Testing

```bash
pytest
```

## What this project demonstrates

- FastAPI application structure
- Request/response validation
- REST endpoint development
- Relational persistence with SQLite
- API testing
- Frontend/backend integration concepts

## Author

**Saad Ouardi**  
[Portfolio](https://saadouardi.vercel.app) · [LinkedIn](https://www.linkedin.com/in/saad-ouardi)
