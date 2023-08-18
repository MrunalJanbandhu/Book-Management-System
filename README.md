# Book-Management-System

The Book Management System is a web-based application that allows users to efficiently manage books, authors, publications, and categories. This README provides an overview of the project, its features, setup instructions, and more.

## Technologies Used

- Frontend: HTML, CSS
- Backend: Java (Spring Boot)
- Database: PostgreSQL
- IDE: IntelliJ IDEA

## Features

- Add, edit, and delete books with associated authors, publications, and categories.
- Render entities as HTML tables using Thymeleaf.
- Maintain data consistency in the PostgreSQL backend.
- Support for CRUD operations on books, authors, and publications.

## Project Structure

- `controller`: Contains controller files.
- `model`: Defines entity classes.
- `repository`: Provides repository interfaces.
- `service`: Implements service logic and interfaces.
- `BookManagementApplication.java`: Main application class.

## Getting Started

1. Ensure PostgreSQL is running on port 5432.
2. Update PostgreSQL username and password in `application.properties`.
3. Create a database named "bookmanagement" in PostgreSQL.
4. Run the `BookManagementApplication.java` file.
5. Access the application at `http://localhost:8088/books` in a web browser.

## Possible Future Work

- Grouping books by author, category, or publisher.
- Adding an edit option for existing entity details.
- Implementing book tracking for availability.
