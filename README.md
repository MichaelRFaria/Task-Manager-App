## Task-Manager-App
## Overview
This project is my first attempt at a full-stack project.
I wanted to get familarised with full-stack development to perpare me for my "Individual Project" module for my final year of university, where I wanted to build the largest scale project I've ever worked on.
I decided to make a simple task manager program as I saw the scalability potential, from being a simple, barebones CRUD app to a highly customisable, and extensive productivity app. 

- React was chosen due to prior experience and its widespread use.
- Spring Boot was chosen due to it being a Java framework, and Java being a langague I have worked with extensively.
- PostgreSQL was chosen due to prior experience and its compatability with Spring Boot.

## Features
- Task management (adding, updating and deleting tasks)
- Filtering and sorting tasks

## Gallery
<p align="center">
  <img width="640" height="360" alt="Dashboard screen" src="https://github.com/user-attachments/assets/b0024076-b739-4cc1-9410-73b8d10cf2bb" />
  <br>
 <em>Dashboard screen</em>
</p>

## Folder structure
 - `\backend\` - Spring Boot application (backend)
 - `\frontend\` - React application (frontend)

## Running the Application
### Requirements
 - Java 17+
 - Node.js 20.17.0+
 - PostgreSQL 18+

## Database setup
1. Create a PostgreSQL database called `task_manager_db`
(Tables will be auto-generated via Hibernate when you run the backend, additionally the default admin user is used to access the database.)

## Backend setup
1. Navigate to the `backend` directory
2. Run using: `./mvnw spring-boot:run`

(Backend runs on: http://localhost:8080)

## Frontend setup
1. Navigate to the `frontend` directory
2. Run using: `npm install`, once installation is complete, run `npm start`

(Frontend runs on: http://localhost:3000)


