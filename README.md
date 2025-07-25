# Full Stack Employee Management System

A full-stack web application built with **Spring Boot** and **Angular** for managing employee data, featuring user authentication, CRUD operations, and a dashboard UI. The backend APIs are secured with JWT, and the application is deployed on AWS.

## Technologies Used

- Backend: Spring Boot, Java, PostgreSQL  
- Frontend: Angular 8+  
- Deployment: AWS EC2, AWS S3, Docker  
- Authentication: JWT (JSON Web Tokens)  
- CI/CD: GitHub Actions  
- API Testing: Postman  

## Features

- User registration and login with role-based access control  
- Create, Read, Update, Delete (CRUD) operations for employee records  
- Responsive dashboard displaying employee statistics  
- Secure REST API endpoints using JWT authentication  
- Dockerized backend and frontend for easy deployment  

## Setup Instructions

### Backend

1. Clone the repository  
2. Navigate to the backend directory  
3. Configure your PostgreSQL database connection in `src/main/resources/application.properties`  
4. Run the backend server using:
   ```bash
   mvn spring-boot:run
