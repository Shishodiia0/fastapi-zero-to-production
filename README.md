# FastAPI Backend API

A backend REST API built using **FastAPI** and **PostgreSQL**.

## Features
- Create posts
- Read posts
- Update posts
- Delete posts
- PostgreSQL database integration
- Pydantic schema validation

## Tech Stack
- Python
- FastAPI
- PostgreSQL
- Psycopg2
- Pydantic

## Project Structure

fastapi_backend
│
├── app
│   └── main.py
│
├── .gitignore
├── requirements.txt
└── README.md


## Setup Instructions

1. Clone the repository

git clone <repo-url>


2. Create a virtual environment

python -m venv venv


3. Activate virtual environment

Mac/Linux:
source venv/bin/activate

Windows:
venv\Scripts\activate

4. Install dependencies


pip install -r requirements.txt


5. Run the server


uvicorn app.main:app --reload


## API Endpoints

| Method | Endpoint | Description |
|------|------|------|
| GET | /posts | Get all posts |
| GET | /posts/{id} | Get single post |
| POST | /posts | Create post |
| PUT | /posts/{id} | Update post |
| DELETE | /posts/{id} | Delete post |

## Future Improvements
- JWT Authentication
- User system
- Docker support
- Testing with Pytest
