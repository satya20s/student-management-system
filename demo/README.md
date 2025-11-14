# Student Management System - Spring Boot + MySQL

This is a simple Student Management CRUD application built using:
- Spring Boot 3.2.7
- Java 17
- MySQL Database
- Spring Data JPA
- RESTful API Architecture

## Features
✔ Add new students  
✔ Get list of all students  
✔ Get single student by ID  
✔ Update student details  
✔ Delete student  
✔ Auto table creation using Hibernate

## Project Structure
- `entity` → Student model
- `repository` → JPA repository
- `service` → Business logic
- `controller` → REST API endpoints

## API Endpoints

### Add Student
`POST /students`

### Get All Students
`GET /students`

### Get Student By ID
`GET /students/{id}`

### Update Student
`PUT /students/{id}`

### Delete Student
`DELETE /students/{id}`

## How to Run
1. Install MySQL and create database:
   ```sql
   CREATE DATABASE studentdb;
