# Student Management REST API

A simple Spring Boot backend application that provides RESTful APIs
to manage student data with basic CRUD operations.

## Tech Stack
- Java
- Spring Boot
- Spring Data JPA
- Hibernate
- MySQL / H2 Database
- REST APIs

## Project Structure
- Controller layer handles HTTP requests
- Service layer contains business logic
- Repository layer interacts with the database
- Entity layer represents database tables

## Features
- Add a student
- Get all students
- Get student by ID
- Update student details
- Delete a student

## API Endpoints
- POST    /api/students
- GET     /api/students
- GET     /api/students/{id}
- PUT     /api/students/{id}
- DELETE  /api/students/{id}

## How to Run
1. Clone the repository
2. Configure database in `application.properties`
3. Run the application using:
4. Test APIs using curl or Postman

## Author
Samay Pathak
