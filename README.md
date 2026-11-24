# Library Management REST API

A Flask REST API for managing books in a library.

## Features
- Create, read, update and delete books.
- Filter by author, genre and year.
- Interactive Swagger UI at /api-docs.
- Docker support.

## Run with Docker
```bash
docker build -t library-api .
docker run -p 5000:5000 library-api
```
The API is on port 5000.
