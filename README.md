# Corporate CRM System

A Java-based web application built with Spring Boot for managing companies, employees, and agreements. It features secure authentication and uses JTE for server-side template rendering.

## Key Features
* User Authentication and Authorization (Spring Security).
* Management interfaces for Companies, Employers, and Agreements (CRUD operations).
* Database versioning and migrations via SQL scripts.
* Server-side rendering using JTE (Java Template Engine).

## Tech Stack
* **Backend:** Java, Spring Boot, Spring Security
* **Frontend:** JTE (Java Template Engine), HTML/JS
* **Database Management:** SQL Migrations (Flyway/Custom)
* **Build Tool:** Maven

## Project Structure
* `controller/`: Request routing and view management.
* `data/Entitys/`: Data models and database repositories (Agreement, Companie, Employer).
* `data/auth/` & `data/security/`: User registration, login handling, and security configuration.
* `src/main/jte/`: Frontend templates (home, login, registration, entity management views).
* `resources/db/migration/`: SQL scripts for database initialization and seeding.

## Running Locally

1. Clone the repository:
   ```bash
   git clone [https://github.com/Vladimir-Iluk/](https://github.com/Vladimir-Iluk/)[YOUR_REPO_NAME].git
   cd [YOUR_REPO_NAME]
Run the application using the Maven Wrapper:

Linux/macOS:

Bash
./mvnw spring-boot:run
Windows:

DOS
mvnw.cmd spring-boot:run
Access the application:
Open a web browser and navigate to http://localhost:8080
