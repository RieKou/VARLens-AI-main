# Development

Backend: `cd backend; python -m venv .venv; .venv/Scripts/pip install -r requirements.txt; .venv/Scripts/uvicorn app.main:app --reload`

Frontend: `cd frontend; npm install; npm run dev`

Set `NEXT_PUBLIC_API_URL=http://localhost:8000/api/v1`. The OpenAPI contract is served at `/docs`.
