# Student API by (Go + Gin + SQLite)
REST API for managing student records.

## Features

- **Create Student**: POST /students

- **Get All Students**: GET /students

- **Get Student by ID**: GET /students/:id

- **Update Student**: PUT /students/:id

- **Delete Student**: DELETE /students/:id

- **Input Validation**: Ensures valid GPA (0.00-4.00) and required fields.

## How to Run

1. Clone the repository

2. Install dependencies:

   ```bash

   go mod tidy

3. Run the server:

   ```bash

   go run main.go

4. API will run at http://localhost:8080
