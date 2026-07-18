# JWT Authentication Hands-on

This repository contains the practical implementations of JWT-based authentication developed during **Module 7 – Spring REST with Spring Boot 3**. The exercises demonstrate how Spring Security and JSON Web Tokens (JWT) can be used to secure RESTful web services.

---

# Project Overview

The project focuses on implementing authentication and authorization in a Spring Boot application. It covers the complete authentication flow, from basic security configuration to protecting REST endpoints with JWT.

---

# Exercises Completed

## Exercise 1 – Spring Security Setup

- Configured Spring Security within the application.
- Established the initial security configuration.

## Exercise 2 – Basic Authentication

- Implemented HTTP Basic Authentication.
- Verified user authentication using credentials.

## Exercise 3 – Authentication Endpoint

- Developed a REST API to authenticate users.
- Processed authentication requests through Spring Security.

## Exercise 4 – Authorization Header Processing

- Retrieved and decoded the Basic Authorization header.
- Extracted user credentials for authentication.

## Exercise 5 – JWT Token Creation

- Generated JWT tokens after successful login.
- Included token creation logic for authenticated users.

## Exercise 6 – JWT Validation

- Verified incoming JWT tokens.
- Implemented a custom JWT filter.
- Secured REST endpoints using Bearer token authentication.

---

# Technology Stack

- Java 17
- Spring Boot
- Spring Security
- JSON Web Token (JWT)
- Maven

---

# Project Structure

```text
JWT-handson
│
├── src/
├── pom.xml
├── mvnw
├── mvnw.cmd
└── HELP.md
```

---

# Running the Project

To execute the application:

1. Import the project into IntelliJ IDEA or any compatible Java IDE.
2. Allow Maven to download and configure all required dependencies.
3. Launch the Spring Boot application.
4. Send an authentication request to the `/authenticate` endpoint to receive a JWT.
5. Include the generated token in the `Authorization: Bearer <token>` header while accessing secured REST APIs.

---

# Learning Outcomes

This project provides hands-on experience with:

- Configuring Spring Security
- Implementing Basic Authentication
- Creating authentication APIs
- Generating and validating JWT tokens
- Building custom JWT filters
- Securing REST services with token-based authentication

---

## Author

**Kaushal Kishor**
