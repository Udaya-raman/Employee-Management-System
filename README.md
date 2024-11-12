# Employee Management System
A web-based application designed to simplify and automate the management of employee information. This system provides efficient CRUD operations, a user-friendly interface, and seamless integration between the frontend and backend.

## Table of Contents
1. [Introduction](#introduction)
2. [Tech Stack](#tech-stack)
3. [Features](#features)
4. [System Architecture](#system-architecture)
5. [Data Flow Diagram](#data-flow-diagram)
6. [Components Explanation](#components-explanation)
7. [Setup and Execution](#setup-and-execution)
8. [API Endpoints](#api-endpoints)
9. [Future Scope](#future-scope)
10. [Contact](#contact)

## Introduction
The Employee Management System is a full-stack web application aimed at streamlining employee data management. The system offers functionalities to add, update, delete, and view employee details, making manual processes error-free and efficient.

## Tech Stack
- **Frontend**: Angular
- **Backend**: Spring Boot
- **Database**: MySQL

## Features
1. **Home Page**: Overview of the system.
2. **View Employees**: List all employees with their details.
3. **Add Employee**: Add a new employee record.
4. **Update Employee**: Edit existing employee information.
5. **Delete Employee**: Remove employee data.

## System Architecture
Below is a simple architecture diagram showcasing the components and their interaction:
- **Frontend (Angular)**: User interface for interacting with the application.
- **Backend (Spring Boot)**: Processes requests and handles business logic.
- **Database (MySQL)**: Stores employee records persistently.
- **REST API**: Enables communication between the frontend and backend.

## Data Flow Diagram
*(Include the data flow diagram here if available)*

## Components Explanation

### Frontend (Angular)
- **Purpose**: Create a responsive and user-friendly interface for users to interact with the system.
- **Key Features**:
  - Dynamic rendering of employee data.
  - Forms for CRUD operations.
  - REST API integration with backend.

### Backend (Spring Boot)
- **Purpose**: Act as the server for handling requests, processing business logic, and interacting with the database.
- **Key Features**:
  - REST API endpoints for CRUD operations.
  - Exception handling using `ResourceNotFoundException`.
  - Security configurations for future enhancements.

### Database (MySQL)
- **Purpose**: Persistent storage for employee data.
- **Structure**: The database contains a table named `employees_table` with columns for `id`, `fname`, `lname`, `email`, `salary`, `department`, `designation`, and `joiningDate`.

## Setup and Execution

### Prerequisites
- Node.js and npm
- Angular CLI
- Java (JDK 8 or higher)
- MySQL Server
- Spring Boot

### Steps to Run the Project

#### Frontend (Angular)
1. Navigate to the frontend directory:
   ```bash
   cd frontend
2. Install dependencies:
   ```bash
   npm install
3. Start the Angular development server:
   ```bash
   ng serve
4. Open your browser and navigate to http://localhost:4200.

#### Backend (Spring Boot)
1. Navigate to the backend directory:
   ```bash
   cd backend
2. Update the application.properties file with your MySQL credentials:
   ```bash
   spring.datasource.url=jdbc:mysql://localhost:3306/emp
   spring.datasource.username=<your-username>
   spring.datasource.password=<your-password>
3. Run the Spring Boot application:
   ```bash
   mvn spring-boot:run
4. The backend server will start on http://localhost:8080.

#### Database Setup 
1. Create a database named emp in MySQL:
   ```bash
   CREATE DATABASE emp;
2. The application will automatically create the employees_table on the first run.

## API Endpoints

### Fetch All Employees
- **Endpoint**: `GET /api/v1/employees`
- **Description**: Retrieve all employee records.

### Add Employee
- **Endpoint**: `POST /api/v1/employees`
- **Description**: Add a new employee to the database.

### Fetch Employee By ID
- **Endpoint**: `GET /api/v1/employees/{id}`
- **Description**: Retrieve employee details by their ID.

### Update Employee
- **Endpoint**: `PUT /api/v1/employees/{id}`
- **Description**: Update details of an existing employee.

### Delete Employee
- **Endpoint**: `DELETE /api/v1/employees/{id}`
- **Description**: Delete an employee record by ID.

## Future Scope
1. **Authentication and Authorization**: Add role-based access control.
2. **Reporting and Analytics**: Generate reports and visualize data trends.
3. **Cloud Deployment**: Host the system on platforms like AWS or Azure for scalability.

## Contact
- chintavishnupriya45@gmail.com
- udayaudayarr@gmail.com
- princepanjiyar02@gmail.com

   
   

    
