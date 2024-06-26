# Employee-Management-System

## Overview

This project is an Express.js RESTful API backend with MongoDB, designed to manage user and employee data. It features user authentication with JWT, allowing users to sign up, log in, and access protected routes. Employees can be created, retrieved, updated, and deleted, with support for pagination, sorting, and filtering. The API is documented using Swagger, facilitating easy understanding and integration. Deployment on platforms like Render is supported. With a clean and well-structured codebase, this project serves as a robust foundation for building scalable web applications requiring user and employee management functionalities.


## deployed links 
 ### backend 
 ```bash
 https://all-backend-servers.onrender.com
 ```

 ### frontend
 ```bash
 https://all-backend-servers.onrender.com
 ```

 ### SwaggerDoc
 ```bash
 https://all-backend-servers.onrender.com/api-docs/
 ```

## Tech Stack

- Node.js
- Express.js
- JWT
- bcrypt
- MongoDB
- Swagger
- HTML
- CSS
- JavaScript
- GitHub

## Features

- User authentication with JWT
- User signup and login
- CRUD operations for employees
- Pagination, sorting, and filtering for employees
- Swagger documentation
- Deployment on platforms like Render

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/abhaysinh-gaikwad/Employee-Management-System.git
   ```

2. Install dependencies:

```bash
npm install
```
3. Set up environment variables:

```bash
Create a .env file based on the .env.example template.
Add your MongoDB connection URI and JWT secret key.
```
4. Run the server:

```bash
npm start
```


5. API Documentation


- Swagger documentation can be accessed at 
```bash
https://all-backend-servers.onrender.com/api-docs
``` 
- endpoint after starting the server

```bash
http://http://localhost:3000/api-docs
```
6. # Endpoints
### User Routes

- Signup
```bash
POST /users/signup
: Sign up a new user.
```
- Login
```bash
POST /users/login
: Log in an existing user.
```
- Logout
```bash
GET /users/logout
: Log out the currently authenticated user.
```
- User Details
```bash
GET /users/details
: Get details of the currently authenticated user.
```

### Employee Routes
- Create Employee
```bash
POST /employees
: Create a new employee.
```
- Get All Employees
```bash 
GET /employees
: Get a list of all employees.
```
- Get Employee by ID
```bash
GET /employees/
: Get details of a specific employee by ID.
```
- Update Employee
```bash
PATCH /employees/
: Update details of a specific employee by ID.
```
- Delete Employee
```bash
DELETE /employees/
: Delete a specific employee by ID.
```
