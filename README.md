# Hiring-Platform

This is a backend solution for a hiring platform built with Java, Spring Boot, and MySQL. The platform assists students to find part-time jobs while companies can post job opportunities. It includes core features like **user authentication**, **job management**, **category management**, and **hiring processing**.

## Features:
- **Handling the hiring process**: The system handles the hiring process, which is carried out by the students and companies. This frees up time for both parties and makes it easier to find a mutually beneficial match.
- Reviews feature: The system incorporates a reviews feature where employers can offer feedback and reviews for job seekers/students upon the successful completion of their part-time engagements. This helps students to get valuable feedback on their work and to improve their skills and knowledge.
- **AI-powered resources**: The system incorporates a comprehensive suite of AI-powered resources to assist students in crafting compelling and professional resumes. This helps students to create resumes that are tailored to their specific skills and experience and that will help them to stand out to potential employers.
- **Experience certificate**: The job provider can add an experience certificate after the student is done with their training. This can be a valuable addition to the student's resume and can help them to get a job after graduation.
- **Job alerts**: Tamakan will send job alerts to the students' email addresses who are matched with the job criteria. This ensures that students are always up-to-date on the latest job openings and that they have the opportunity to apply for jobs that are a good fit for their skills and interests.

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
