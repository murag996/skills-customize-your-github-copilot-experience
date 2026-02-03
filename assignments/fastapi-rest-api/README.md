# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Learn how to design and implement RESTful APIs using the FastAPI framework in Python. Students will create a simple API for managing resources and practice handling requests, responses, and data validation.

## 📝 Tasks

### 🛠️	Task 1: Set Up FastAPI Project

#### Description
Initialize a new FastAPI project and create a basic API endpoint that returns a welcome message.

#### Requirements
Completed program should:

- Install FastAPI and Uvicorn
- Create a main application file (main.py)
- Implement a root endpoint (`/`) that returns a JSON welcome message


### 🛠️	Task 2: Create CRUD Endpoints

#### Description
Design and implement RESTful endpoints for a simple resource (e.g., "items" or "books"). Support Create, Read, Update, and Delete operations.

#### Requirements
Completed program should:

- Define a Pydantic model for the resource
- Implement endpoints for:
  - Creating a new resource
  - Retrieving all resources
  - Retrieving a single resource by ID
  - Updating a resource
  - Deleting a resource
- Validate input data and return appropriate responses

### 🛠️	Task 3: Test Your API

#### Description
Test your API using an HTTP client (such as curl, Postman, or FastAPI's interactive docs).

#### Requirements
Completed program should:

- Demonstrate successful requests for each endpoint
- Handle errors gracefully (e.g., resource not found)
- Document your API endpoints using FastAPI's built-in documentation

---

**Learning Tips:**
- Review FastAPI documentation: https://fastapi.tiangolo.com/
- Use clear variable names and comments in your code
- Ask questions if you get stuck!

**Difficulty:** Beginner to Intermediate

**Estimated Time:** 1-2 hours

