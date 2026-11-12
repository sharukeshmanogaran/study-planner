# Placement & Study Planner (Full-Stack Spring Boot Web App)

A full-stack web application built with Java 21, Spring Boot, Spring Data JPA, H2 Database, and HTML/CSS/JavaScript to organize study topics and placement preparation tasks.

## Features
- **RESTful API Architecture:** Exposes `GET`, `POST`, `PUT`, and `DELETE` endpoints (`/api/tasks`) using Spring Web (`@RestController`).
- **Relational Database Persistence:** Maps Java entities (`@Entity`) directly to SQL tables via Spring Data JPA and an embedded H2 database.
- **Interactive Frontend:** Responsive dark-mode single-page interface using vanilla JavaScript `fetch()` API for asynchronous CRUD operations without page reloads.

## Tech Stack
- **Backend:** Java 21, Spring Boot, Spring Web, Spring Data JPA
- **Database:** H2 Relational Database
- **Frontend:** HTML5, CSS3, JavaScript (Fetch API)
- **Build Tool:** Maven

## How to Run
1. Run `StudyPlannerApplication.java` (or execute `./mvnw spring-boot:run`).
2. Open `http://localhost:8080` in any web browser.
3.