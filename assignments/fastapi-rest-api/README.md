# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Learn how to design and implement RESTful APIs using the FastAPI framework in Python. By the end of this assignment, you will understand how to create endpoints, handle requests and responses, and structure a simple API project.

## 📝 Tasks

### 🛠️  Set Up FastAPI Project

#### Description
Initialize a new FastAPI project and set up the basic structure for your API.

#### Requirements
Completed program should:

- Install FastAPI and Uvicorn
- Create a main application file (e.g., main.py)
- Set up a root endpoint (GET /) that returns a welcome message

### 🛠️  Implement CRUD Endpoints

#### Description
Add endpoints to perform Create, Read, Update, and Delete (CRUD) operations for a simple resource (e.g., items, books, or users).

#### Requirements
Completed program should:

- Define a Pydantic model for the resource
- Implement endpoints for:
  - Creating a new resource (POST)
  - Retrieving all resources (GET)
  - Retrieving a single resource by ID (GET)
  - Updating a resource by ID (PUT)
  - Deleting a resource by ID (DELETE)
- Return appropriate status codes and JSON responses

#### Example

```
POST /items {"name": "Book", "price": 10.99}
GET /items
GET /items/1
PUT /items/1 {"name": "Updated Book", "price": 12.99}
DELETE /items/1
```
