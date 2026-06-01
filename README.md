# SecurityApp 🔐

A comprehensive Spring Boot Security project implementing modern authentication and authorization mechanisms using Spring Security, JWT, OAuth2, Refresh Tokens, Role-Based Access Control (RBAC), and Permission-Based Authorization.

## Features

### Authentication

* User Registration (Signup)
* User Login
* JWT Access Token Authentication
* Refresh Token Support
* Secure Password Encryption using BCrypt

### Authorization

* Role-Based Authorization
* Permission/Authority-Based Access Control
* Protected REST Endpoints
* Method-Level Security

### OAuth2 Integration

* Google OAuth2 Login
* OAuth2 Client Configuration
* Social Authentication Support

### Security Enhancements

* Custom JWT Authentication Filter
* SecurityFilterChain Configuration
* Session Management
* Custom Exception Handling
* Authentication & Authorization Error Responses

## Tech Stack

* Java 17+
* Spring Boot
* Spring Security
* Spring Data JPA
* Hibernate
* MySQL
* JWT (JSON Web Token)
* OAuth2 Client
* Maven

## Project Structure

```text
src
├── config
├── controller
├── dto
├── entity
├── repository
├── security
├── service
├── exceptions
└── util
```

## Authentication Flow

1. User registers an account.
2. User logs in using credentials.
3. Server generates JWT Access Token and Refresh Token.
4. Access Token is used to access protected APIs.
5. Refresh Token is used to generate a new Access Token when expired.
6. Spring Security validates every request using a custom JWT filter.

## API Security Features

* Stateless Authentication
* JWT Token Validation
* Role-Based Endpoint Protection
* Permission-Based Access Control
* OAuth2 Login Support
* Refresh Token Mechanism
* Custom Security Configuration

## Learning Objectives

This project demonstrates:

* Spring Security Fundamentals
* JWT Authentication
* Refresh Token Implementation
* OAuth2 Authentication
* Session Management
* Role-Based Authorization
* Permission-Based Authorization
* Custom Security Filters
* Exception Handling in Spring Security

## Future Improvements

* Email Verification
* Password Reset
* Two-Factor Authentication (2FA)
* Account Locking Mechanism
* Redis Token Storage
* API Rate Limiting

