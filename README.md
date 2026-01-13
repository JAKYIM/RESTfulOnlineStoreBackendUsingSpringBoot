🛒 Spring Boot Online Store Backend

A RESTful backend application for an online store, built using Spring Boot.
This project implements core e-commerce functionalities such as user management, product handling, and message processing using a clean, layered architecture.

📌 Features

RESTful APIs for users, products, and messages
DTO-based request/response handling
Layered architecture (Controller, Service, Repository)
Database persistence using Spring Data JPA
Basic validation and exception handling
Maven-based build and dependency management

🏗️ Project Structure
src/
 ├── controllers/     # REST API endpoints
 ├── dtos/            # Data Transfer Objects
 ├── entities/        # JPA entities
 ├── repositories/   # Data access layer
 ├── mappers/        # DTO ↔ Entity mapping
 └── StoreApplication.java

🔗 API Endpoints (Sample)
Method	Endpoint	Description
GET	/api/products	Fetch all products
POST	/api/products	Create a new product
GET	/api/users	Fetch all users
POST	/api/users	Register a new user
POST	/api/messages	Submit a message
🛠️ Tech Stack

Java
Spring Boot
Spring Data JPA
Hibernate
Maven
REST API

⚙️ Setup & Run
Prerequisites

Java 17+ (or compatible)

Maven
Run Locally
./mvnw spring-boot:run

or on Windows:
mvnw.cmd spring-boot:run

Application runs at:
http://localhost:8080

🗄️ Database

Uses relational database configuration via application.yaml
SQL schema/data can be initialized using script.sql

📄 Notes

IDE-specific files (.idea, .run, target) are excluded using .gitignore
Designed for learning, scalability, and clean API practices

🚀 Future Enhancements

Authentication & Authorization (JWT)
Role-based access control
Order and payment modules
Swagger / OpenAPI documentation

👤 Author

Jakyim Jonan F
Backend & Systems Enthusiast
