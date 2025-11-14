# Student Management System (Spring Boot + MySQL)

This is a simple Student Management System built using **Spring Boot**, **MySQL**, and **REST APIs**.

## Features
- Add Student
- Get All Students
- Get Student By ID
- Update Student
- Delete Student

## Technologies Used
- Java 17
- Spring Boot 3
- Spring Data JPA
- MySQL 8
- Maven

## How to Run
1. Clone the project:
   git clone https://github.com/YOUR_USERNAME/student-management-system.git

2. Create database in MySQL:
   CREATE DATABASE studentdb;

3. Update `application.properties`:
   spring.datasource.username=root  
   spring.datasource.password=YourPassword

4. Run the project from IntelliJ:
   DemoApplication.java -> Run

5. Test using browser:
   http://localhost:8080/api/students

## API Endpoints
| Method | Endpoint                     | Description           |
|--------|-------------------------------|------------------------|
| POST   | /api/students                 | Add new student        |
| GET    | /api/students                 | Get all students       |
| GET    | /api/students/{id}            | Get student by ID      |
| PUT    | /api/students/{id}            | Update student         |
| DELETE | /api/students/{id}            | Delete student         |

## Author
Satya

