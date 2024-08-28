# FastAPI Notes Backend

Welcome to the FastAPI Notes Backend! This project provides a simple backend service for managing notes, built with FastAPI.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)

## Features

- Create, read, update, and delete notes.
- Fast and efficient with asynchronous capabilities.
- Easy to extend and modify.
  
## Technologies Used

- [FastAPI](https://fastapi.tiangolo.com/)
- [SQLAlchemy](https://www.sqlalchemy.org/)
- [Pydantic](https://pydantic-docs.helpmanual.io/)
- [PostgreSQL](https://www.postgresql.org/) (or any other database you choose)
- Docker for containerized deployment.

## Installation

### From python:
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/fast_api_notes_backend.git
   cd fast_api_notes_backend
   ```

2. ```python
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. ```python
   pip install -r requirements.txt
   ```

6. ```python
   uvicorn main:app
   ```

### From Docker:

1. ```bash
   git clone https://github.com/yourusername/fast_api_notes_backend.git
   cd fast_api_notes_backend
   ```
2. ```bash
   docker build . --tag fastapi_notes $$ docker run -p 80:80 fastapi_notes
   ```
   
   

