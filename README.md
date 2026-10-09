# Courses Management System

A Java web application for browsing courses, managing enrollments, viewing timetables, and sharing course feedback.

## Overview

The application allows users to create an account, sign in, explore available courses, and manage their registered courses. It also provides views for ongoing and completed courses, course ratings, and student feedback.

The backend uses Java Servlets and JDBC to interact with a MySQL database, while the frontend uses HTML, CSS, and JavaScript.

## Features

- User registration, login, and logout.
- Browsing available courses.
- Course enrollment and withdrawal.
- Viewing ongoing and completed courses.
- Submitting course ratings and feedback.
- Reading feedback from other students.
- Browsing top-rated courses.
- Viewing a timetable with enrolled courses highlighted.

## Technologies

| Area | Technologies |
|---|---|
| Backend | Java, Java Servlets (`javax.servlet`) |
| Frontend | HTML, CSS, JavaScript |
| Database | MySQL |
| Database access | JDBC |
| Test code | JUnit, Mockito |

## Project Structure

| Directory | Contents |
|---|---|
| `main/java/` | Servlets, database access classes, utilities, and test classes. |
| `main/webapp/` | HTML pages, stylesheets, images, and web configuration. |
| `main/Screenshoots/` | Screenshots of the application interface. |

## Main Components

- **User management:** registration, authentication, logout, and session handling.
- **Course management:** course listings, enrollment, withdrawal, and course status views.
- **Feedback:** student comments, ratings, and top-rated course listings.
- **Timetable:** a weekly course view highlighting the user's ongoing enrollments.
- **Database access:** connection handling and queries for users, courses, enrollments, and feedback.

## Setup

1. Import the source into a Java web application project.
2. Configure a servlet container compatible with `javax.servlet`.
3. Add the MySQL JDBC driver to the application's dependencies.
4. Create and populate the MySQL database required by the database access classes.
5. Configure the database connection in `Connector.java` for your local environment.
6. Deploy the application to the servlet container.
7. Open `signup.html` or `login.html` through the deployed application's URL.

**Note:** The provided source does not include a database creation script or a Maven/Gradle build configuration. Database setup and dependency configuration must be completed separately.

## Tests

The project includes test classes for login and registration using JUnit and Mockito. Some tests depend on database records and require an appropriately configured test database.

## Purpose

This project demonstrates Java web development through servlet-based request handling, session management, relational database access, and a course management interface.
