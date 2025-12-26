🎓 Student Management System

Spring Boot REST APIs with JPA, Security, and PostgreSQL
A backend application that provides RESTful APIs to manage students, courses, and grades — designed to showcase backend fundamentals using Java and Spring Boot.

🧠 Overview

This project demonstrates how to build a well-structured backend service with core capabilities such as:

RESTful API design

Secure endpoints using Spring Security (JWT)

Database interaction with Spring Data JPA and PostgreSQL

Entity relationships (students, courses, grades)

API documentation

It was built to strengthen my understanding of backend development using Java and Spring Boot.

🛠️ Tech Stack

Backend

Java

Spring Boot

Spring Data JPA

Spring Security (JWT)

Database

PostgreSQL

Tools

Swagger / OpenAPI for API documentation

Postman for API testing

Maven for build management

JUnit & Mockito for testing

🚀 Features

Create, Read, Update, Delete student records

Manage courses and enrollments

Handle student grades

Secure API routes using JWT authentication

API documentation support with Swagger

🧱 Architecture

The project follows a clean layered approach:

Controller Layer – Handles HTTP requests

Service Layer – Business logic and validation

Repository Layer – Database operations using JPA

Security Layer – JWT token handling and authorization

This structure promotes separation of concerns and easy maintenance.

📌 API Documentation

Swagger/OpenAPI is included to make it easy to explore and test the APIs.

After running the application locally, you can access the Swagger UI (usually at):

http://localhost:8080/swagger-ui.html

🧪 Testing

Unit tests for key service functionality using JUnit and Mockito

Manual API testing with Postman

Documentation aids testing via Swagger

Testing ensures each component behaves as expected before integration.

🚀 How to Run Locally
Prerequisites

Java 17 or higher

PostgreSQL database

Maven

Setup

Clone the repository

git clone https://github.com/NithishKarth1ck/Student-Management-System.git

cd Student-Management-System


Configure PostgreSQL connection in application.properties

Build and run the project

mvn clean install

mvn spring-boot:run


Once running, APIs will be available at:

http://localhost:8080

🧠 What I Learned

This project helped me deepen my understanding of:

Designing clean backend APIs

Securing routes with JWT

Mapping entity relationships with JPA

Documenting APIs using Swagger

Writing basic unit tests

👨‍💻 About Me

I’m an entry-level Java Backend Developer transitioning from a non-technical background into backend development. I focus on writing clear, maintainable code and learning industry-relevant backend practices.

📧 nithishnickzz@gmail.com

🔗 https://www.linkedin.com/in/nithish-karthick-993447355/
