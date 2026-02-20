# CMPS2242 Lab #4: Middleware, Dependency Injection, and Custom Response Writers

**Name:** Jeimy Vasquez  

This project implements a versioned Go API with five endpoints, using middleware for logging, dependency injection for a structured logger, and a custom response writer to capture HTTP status codes.  

## Endpoints

- `GET /v1/healthcheck` – Check server status  
- `GET /v1/books` – List all books  
- `GET /v1/books/{id}` – Get a single book by ID  
- `POST /v1/books` – Create a new book  
- `DELETE /v1/books/{id}` – Delete a book by ID  

## How to Run

1. Open a terminal in the project directory.  
2. Run the server:  
    go run main.go