# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Build a REST API using the FastAPI framework in Python. Create endpoints for basic CRUD operations on a simple data model, such as managing a list of items (e.g., books or tasks).

**Skills practiced:** FastAPI framework, REST API design, HTTP methods, Pydantic models, asynchronous programming

## 📝 Tasks

### 🛠️ Set Up FastAPI Application

#### Description
Install FastAPI and create a basic application structure with a root endpoint that returns a welcome message.

#### Requirements
Completed program should:

- Install FastAPI and Uvicorn
- Create a FastAPI app instance
- Define a GET endpoint at "/" that returns a JSON response with a welcome message
- Run the server and verify the endpoint works

### 🛠️ Implement CRUD Endpoints

#### Description
Create REST API endpoints for Create, Read, Update, and Delete operations on a simple data model (e.g., a list of items with id, name, description).

#### Requirements
Completed program should:

- Define a Pydantic model for the item (e.g., Item with id: int, name: str, description: str)
- Implement GET /items to retrieve all items
- Implement POST /items to create a new item
- Implement GET /items/{item_id} to retrieve a specific item by ID
- Implement PUT /items/{item_id} to update an existing item
- Implement DELETE /items/{item_id} to delete an item
- Use appropriate HTTP status codes and error handling