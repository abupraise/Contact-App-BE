
# Hux Ventures Contact Manager - Backend

## Overview
This is the backend for the Hux Ventures Contact Manager. It provides a RESTful API for managing contact information and user authentication, built using Java Spring Boot.

## Features
- User authentication using JWT (JSON Web Tokens)
- CRUD operations for contacts:
  - Create a new contact
  - Retrieve all contacts
  - Retrieve a single contact by ID
  - Update an existing contact
  - Delete a contact

## Prerequisites
- Java JDK 17 or newer
- Maven (for building the project)
- MySQL Server (database for storing contact & user data)

## Installation

To set up the backend server, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/abupraise/hux-assessment-backend
   cd hux-assessment-backend
   ```

2. Configure MySQL:
   - Ensure MySQL is running on your machine.
   - Create a new database named `HuxContactDB`.
   - Update `src/main/resources/application.yml` with your database username and password.

3. Build the project:
   ```bash
   mvn clean install
   ```

4. Run the server:
   ```bash
   java -jar target/backend-0.0.1-SNAPSHOT.jar
   ```

   The server will start, and the API will be available at `http://localhost:8080`.

## Built With
- [Java Spring Boot](https://spring.io/projects/spring-boot) - The server framework used
- [JWT](https://jwt.io/) - For implementing JSON Web Tokens
- [Spring Data JPA](https://spring.io/projects/spring-data-jpa) - For database integration
- [MySQL](https://www.mysql.com/) - Database used

## Usage
API endpoints are accessible via HTTP requests. They support various functionalities for managing contacts and handling user authentication.

## Authors
- **Praise Abu**
