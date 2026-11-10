# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Learn how to build modern, fast web APIs in Python using the FastAPI framework by creating endpoints, validating request data, and returning JSON responses.

## 📝 Tasks

### 🛠️ Create the Root Endpoint

#### Description
Set up a basic FastAPI application instance and create a root endpoint that returns a welcome message.

#### Requirements
Completed program should:

- Import `FastAPI` from the `fastapi` module.
- Initialize the FastAPI app instance: `app = FastAPI()`.
- Define a GET endpoint at `/` that returns `{"message": "Welcome to the Student API!"}`.

### 🛠️ Create Items Endpoints

#### Description
Implement GET and POST endpoints to retrieve and create student items in memory.

#### Requirements
Completed program should:

- Maintain an in-memory list or dictionary of items.
- Define a GET endpoint at `/items` that returns all items.
- Define a POST endpoint at `/items` that accepts a JSON body and adds the new item.
