# FastAPI CRUD Example

This project demonstrates basic CRUD operations using FastAPI. It includes functionality to create, read, update, and delete posts.

## Setup & Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/aniketp166/FastAPI-python
    cd FastAPI-python
    ```

2. **Create a virtual environment**:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install dependencies**:
    ```bash
    pip install fastapi uvicorn
    ```

## Running the Application

1. **Start the FastAPI server**:
    ```bash
    uvicorn app.main:app --reload
    ```

2. **Access the API documentation**:
    Open your browser and navigate to `http://127.0.0.1:8000/docs`

## API Endpoints

- **GET /**: Root endpoint with a welcome message.
- **GET /posts**: Retrieve all posts.
- **POST /posts**: Create a new post.
- **GET /posts/{id}**: Retrieve a specific post by ID.
- **DELETE /posts/{id}**: Delete a post by ID.
- **PUT /posts/{id}**: Update a post by ID.

