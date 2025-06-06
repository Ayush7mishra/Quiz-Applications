# Quiz Application

A full-stack Quiz Application built using HTML, CSS, and JavaScript on the frontend, and Spring Boot with MySQL on the backend.

## 🌐 Frontend

- HTML, CSS, JavaScript
- Interactive quiz UI
- Handles user inputs and displays questions dynamically

## 🔧 Backend

- **Spring Boot (Java)**: RESTful APIs to serve quiz data, handle submissions, and manage users/scores
- **Postman**: Used for testing and documenting APIs
- **MySQL Workbench**: Manages the quiz data (questions, answers, user scores, etc.)

## 🔗 API Endpoints (Examples)

| Method | Endpoint              | Description              |
|--------|-----------------------|--------------------------|
| GET    | `/api/questions`      | Fetch all quiz questions |
| POST   | `/api/submit`         | Submit answers           |
| GET    | `/api/results/{id}`   | Get result by user ID    |

## ⚙️ How to Run the Project

### 1. Backend

- Make sure MySQL is running and a database is created.
- Update `application.properties` in Spring Boot with your DB config.
- Run the Spring Boot application using your IDE or terminal:
  ```bash
  mvn spring-boot:run
