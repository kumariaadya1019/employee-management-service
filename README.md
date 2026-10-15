# Employee Management API

A robust RESTful Spring Boot microservice designed to handle core employee data operations. This backend system provides secure and efficient endpoints for creating, retrieving, updating, and deleting employee records, built with a focus on high performance and clean architecture.

## 🚀 Technologies Used
*   **Language:** Java 17 (Streams, Lambda Expressions)
*   **Framework:** Spring Boot 3.x, Spring Data JPA, Spring Web
*   **Database:** PostgreSQL (with HikariCP connection pooling)
*   **Build Tool:** Maven
*   **Testing:** JUnit 5, Postman

## ⚙️ Core Features
*   **Multi-layered Architecture:** Implements standard Controller, Service, and Repository layers for clean separation of concerns.
*   **Data Transfer Objects (DTOs):** Utilizes DTOs and Mappers to ensure secure and efficient data transfer between the client and database.
*   **Exception Handling:** Centralized `@ControllerAdvice` for graceful error management and standardized API responses.
*   **Data Validation:** Integrated Spring Boot Validation (Hibernate Validator) for strict entity and request payload constraints.

## 📡 API Endpoints

| HTTP Method | Endpoint | Description |
| :--- | :--- | :--- |
| `GET` | `/api/v1/employees` | Retrieve a list of all employees |
| `GET` | `/api/v1/employees/{id}` | Retrieve a specific employee by ID |
| `POST` | `/api/v1/employees` | Create a new employee record |
| `PUT` | `/api/v1/employees/{id}` | Update an existing employee record |
| `DELETE` | `/api/v1/employees/{id}` | Delete an employee record |

## 🛠️ Local Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/kumariaadya1019-crypto/employee-management-api.git](https://github.com/kumariaadya1019-crypto/employee-management-api.git)
