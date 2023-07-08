# 🚖 TAXI-SERVICE 🚖

## Project Description

A simple web application that provides a taxi service. It supports authentication, registration, and CRUD (Create, Read, Update, Delete) operations for various entities.

## ⚙️ Features

- Registration and authentication for drivers.
- Create, update, and remove manufacturers.
- Create, update, and remove cars.
- Create and update driver details.
- Display lists of all manufacturers, cars, and drivers.
- Display a list of cars for the currently logged-in driver.
- Add a driver to a car.

## 📑 Project Structure (3-layer architecture)

The project follows a 3-layer architecture design:

- **DAO (Data Access Layer):** Handles the interaction with the database.
- **Service (Application Logic Layer):** Contains the business logic and processes the data.
- **Controllers (Presentation Layer):** Handles the HTTP requests and responses.

## ⚙️ Used Technologies and Libraries

The following technologies and libraries were used in this project:

- Java 19
- Git
- Apache Maven
- Apache Tomcat (version 9.0.5)
- MySQL
- JDBC
- Javax Servlet
- JSP (JavaServer Pages)
- JSTL (JavaServer Pages Standard Tag Library)
- HTML/CSS
- Checkstyle plugin

## 👟 Steps to Run the Program on Your Computer

To run the program on your computer, follow these steps:

1. Clone the repository from [here](repository-link).
2. Install MySQL on your computer.
3. Configure Apache Tomcat with the required version (IMPORTANT: Version 9.0.5).
4. Copy and run the SQL script located at `/src/main/resources/init_db.sql`. This script will create the necessary schema and tables for the project.
5. Configure `/src/main/java/taxi/util/ConnectionUtil.java` with your database connection details, including the URL, username, password, and JDBC driver.
6. You're done! Now you can try using the taxi service application. 🎉

[repository-link]: #insert-your-repository-link