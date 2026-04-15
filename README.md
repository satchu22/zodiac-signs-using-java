# Zodiac Signs Using Java

A full-stack Zodiac Sign Finder built with **Java Spring Boot**.  
Users enter their **name** and **birth date**, and the application calculates their zodiac sign, displays the result with related images, and stores the submitted user data in a **MySQL** database.

## Features

- Zodiac sign calculation based on date of birth
- User-friendly form to enter name and birth date
- Displays zodiac result with related images
- Stores user details in MySQL
- Built using Spring Boot and Spring Data JPA
- Containerized with Docker and Docker Compose

## Tech Stack

- **Backend:** Java, Spring Boot
- **Database:** MySQL
- **ORM/Data Access:** Spring Data JPA
- **Containerization:** Docker, Docker Compose
- **Frontend:** HTML, CSS, Thymeleaf/JSP (depending on your implementation)

## How It Works

1. The user enters their name and date of birth.
2. The application processes the birth date.
3. It determines the correct zodiac sign.
4. The result page shows the zodiac sign with a matching image.
5. The submitted data is stored in the MySQL database.

## Project Structure

```bash
zodiac-signs-using-java/
│── src/
│   ├── main/
│   │   ├── java/         # Java source files
│   │   ├── resources/    # application.properties, templates, static files
│── Dockerfile
│── docker-compose.yml
│── pom.xml
│── README.md
