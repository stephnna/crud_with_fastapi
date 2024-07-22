# FastAPI CRUD Application

This is a simple CRUD (Create, Read, Update, Delete) application built using FastAPI, SQLAlchemy, and SQLite.

## Features

- Create new items
- Retrieve an item by ID
- Retrieve all items
- Update an item by ID
- Delete an item by ID

## Installation

### Prerequisites

- Python 3.8 or higher
- pip (Python package installer)

### Setup

1. **Clone the repository:**

   ```bash
   git clone git@github.com:stephnna/crud_with_fastapi.git
   cd crud_with_fastapi

python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

pip install -r requirements.txt

### Run
uvicorn main:app --reload

Access the interactive API documentation:

Swagger UI: http://127.0.0.1:8000/docs
ReDoc: http://127.0.0.1:8000/redoc

