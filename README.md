# Student Management System

This is a full-stack web application used to manage student records. The project is built using Java, Spring Boot, Spring Data JPA, HTML, CSS, and JavaScript. It allows users to perform basic CRUD operations on student data.

## Features

- Add a new student
- View all student records
- Get student details by ID
- Update student record by ID
- Delete student record by ID

## Student Details

Each student record contains:
- ID
- Name
- Email

## Technologies Used

- Java
- Spring Boot
- Spring Data JPA
- H2 Database / MySQL
- HTML
- CSS
- JavaScript

## API Endpoints

- `GET /Student` - Get all students
- `GET /Student/{id}` - Get student by ID
- `POST /Student` - Create a new student
- `PUT /Student/{id}` - Update student by ID
- `DELETE /Student/{id}` - Delete student by ID

## Project Architecture

The project follows a layered architecture:

- `Controller` handles HTTP requests
- `Service` contains business logic
- `Repository` interacts with the database
- `Model` represents the student entity

## Conclusion

This project is useful for learning CRUD operations, REST API development, Spring Boot basics, and database integration.
