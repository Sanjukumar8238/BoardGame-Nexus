# Boardgame Listing Web Application

## Overview

This project is a full-stack web application designed to serve as a comprehensive database for board games and their reviews. Users can browse board game lists and read reviews without logging in, but must sign in to contribute by adding or editing content. There are three roles: non-members, users, and managers, each with distinct permissions. Users can contribute by adding games and reviews, while managers have additional privileges to modify or delete reviews.

## Tech Stack

- **Java**
- **Spring Boot**
- **Amazon Web Services (AWS) EC2**
- **Thymeleaf**
- **Thymeleaf Fragments**
- **HTML5**
- **CSS**
- **JavaScript**
- **Spring MVC**
- **JDBC**
- **H2 In-Memory Database**
- **JUnit Testing Framework**
- **Spring Security**
- **Twitter Bootstrap**
- **Maven**

## Core Features

- **Full-Stack Implementation:** Built with Java and Spring Boot, with a responsive UI using Thymeleaf and Bootstrap.
- **Role-Based Access Control:**
  - **Non-Members:** Can view board game listings and reviews.
  - **Users:** Can add new board games and submit reviews.
  - **Managers:** Have the additional ability to edit and delete reviews.
- **Authentication & Authorization:** User authentication is managed through Spring Security, with role-based authorization ensuring appropriate access levels.
- **CRUD Operations:** Full support for creating, reading, updating, and deleting entries in the database, facilitated by JDBC.
- **AWS Deployment:** The application is deployed on an AWS EC2 instance, ensuring scalability and accessibility.
- **Thymeleaf Templates:** Utilizes Thymeleaf fragments to avoid redundancy in HTML templates.
- **Testing:** Unit tests are implemented using the JUnit framework to ensure robust and reliable code.
- **Database Initialization:** A schema.sql file is used to configure the database schema and load initial data.

## Running the Application

### Setup Instructions

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/boardgame-listing-app.git
   ```
2. **Open the Project:** Use your preferred IDE to open the project.
3. **Run the Application:** Start the application within your IDE or using Maven commands.
4. **Initial Credentials:**
   - **User Role:**
     - Username: `bugs`
     - Password: `bunny`
   - **Manager Role:**
     - Username: `daffy`
     - Password: `duck`
5. **Sign Up:** Alternatively, you can register as a new user and explore the application with your chosen role.

## Additional Information

This application follows Spring MVC best practices, ensuring a clean separation between the views, controllers, and data access layers. The use of Thymeleaf fragments streamlines the development of consistent, maintainable HTML components. The project also incorporates unit testing with JUnit to validate functionality and ensure code reliability.

## Contribution

Contributions are welcome! Feel free to fork this repository, submit pull requests, or report issues.
