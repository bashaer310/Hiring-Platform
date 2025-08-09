# Hiring-Platform

This is a backend solution for a hiring platform built with Java, Spring Boot, and MySQL. The platform assists students to find part-time jobs while companies can post job opportunities. It includes core features like **user authentication**, **job management**, **category management (types of job)**, and **hiring processing**.

## Features:
- **User Management**:
  - **User Registration** - users can create an account (job Provider/job seeker)
  - **Authentication & Authorization** - users can login with role-based access
  - **Profile Management** - users can update their profile
 
- **Job Management**:
  - **Job Posting** - Job providers can create, update, and delete job postings (title, description, requirements, salary)
  - **Job Browsing** - Job seekers can retrieve available jobs with pagination and filters
  - **Job Details** - Job seekers can view job descriptions and requirements
  - **Job Notification** - Job seekers will receive email alerts for new job postings
    
- **Category Management (types of job)**:
  - **Category Management** - admin can create, update, and delete categories (e.g., software development, IT support, data analysis, cybersecurity)
  - **Category Listing** - users can retrieve categories with pagination and filtering
    
- **Hiring Processing**: 
  - **Application Submission** - Job seekers can apply for posted jobs
  - **Application Tracking** - Job seekers can view their application status
  - **Application Status Management** - Job providers can review applicationn and update status (pending, interview scheduled, hired, rejected)


## Technologies Used
- Languages
    - Java 21 – Programming language
    
- Frameworks
    - Spring Boot – RESTful API framework
      
- Datebase
    - MySQL – Relational database
 
- Dependencies
    - Spring Data JPA (Hibernate) – ORM for database access
    - Spring Security (JWT) – Authentication and authorization
    - Bean Validation – Input validation
    - Lombok – Reduces boilerplate code
    - JUnit 5 – Testing framework
    - Spring Boot Test – Test support for Spring apps
      
- Dependency manger
    - Maven – Dependency and build management
      
- Tools
    - Postman – API testing

## Getting Started

1. Clone the repository:
  ```bash
  git clone https://github.com/bashaer310/Hiring-Platform
  ```

2. Navigate to the project folder:
  ```bash
  Hiring-Platform
  ```

3. Configure Database:
- Ensure MySQL is running.
- Create tables for all the models in your DB.
- Open `src/main/resources/application.properties` and update the DB config:

```bach
  spring.datasource.url=jdbc:mysql://localhost:3306/yourDB
  spring.datasource.username=yourUsername
  spring.datasource.password=yourPassword
```

- Run the application:

  Use your IDE or run via command line:
```bash
./mvnw spring-boot:run
```
5. Test the API

    Use tools like Postman to test the endpoints.


## Project structure
```bash
Hiring-Platform/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/example/Hiring/
│   │   │       ├── controller/       # API controllers for handling requests and responses
│   │   │       ├── config/           # Security and application configurations
│   │   │       ├── dto/              # Data Transfer Objects
│   │   │       ├── model/            # JPA entities (models)
│   │   │       ├── advice/           # Custom exceptions and hanling
│   │   │       ├── repository/       # Spring Data JPA repositories
│   │   │       ├── service/          # Business logic and services
│   │   │       └── FreelanceApplication.java  # Application entry point
│   │   ├── resources/
│   │   ├── application.properties    # App configuration and DB connection
├── pom.xml                           # Maven configuration file
```

## API Endpoints
All the API endpoints are documented and can be accessed at: [Post man](https://documenter.getpostman.com/view/28987531/2s9YC2zDDy)

## Deployment
The application is deployed and can be accessed at: 

## Team Members 
- [Bashaer Alhuthali](https://github.com/bashaer310)
- [Mariam Almesfer](https://github.com/MariamAlmesfer)
- [Manayer Hamad](https://github.com/Manayer12)

## License
This project is licensed under the MIT License.
