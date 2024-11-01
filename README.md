# Spring Security Programs

This repository contains Spring Security examples and implementations for various authentication and authorization mechanisms, including Basic Authentication, Basic Authorization, JWT Authentication & Authorization, and OAuth 2.0. Each module provides a practical example to help you secure applications built with Spring Boot and MongoDB.

## Table of Contents

- [Introduction](#introduction)
- [Technologies Used](#technologies-used)
- [Topics Covered](#topics-covered)
  - [Basic Authentication](#basic-authentication)
  - [Basic Authorization](#basic-authorization)
  - [JWT Authentication and Authorization](#jwt-authentication-and-authorization)
  - [OAuth 2.0](#oauth-20)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)

---

## Introduction

This repository is designed as a learning resource for Spring Security with MongoDB. Each security mechanism is implemented as a standalone module with examples and explanations, making it easier to understand how to apply these techniques in your applications.

## Technologies Used

- **Spring Boot** - To simplify setup and configuration.
- **Spring Security** - For implementing various security mechanisms.
- **Java JDK 21** - To leverage the latest Java features.
- **MongoDB** - As the database for storing user and role information.
- **Maven** - For dependency management.

## Topics Covered

### Basic Authentication

Basic Authentication is a straightforward way to secure endpoints. This example demonstrates:
- Enabling HTTP Basic Authentication.
- Configuring user roles and passwords stored in MongoDB.
- Protecting API endpoints based on user roles.

### Basic Authorization

Authorization adds role-based access control to the application. This module includes:
- Setting up role-based access control using MongoDB for user and role management.
- Utilizing annotations such as `@PreAuthorize` and `@Secured`.
- Implementing method-level authorization for fine-grained access control.

### JWT Authentication and Authorization

JSON Web Tokens (JWT) are a popular choice for securing RESTful APIs. This module covers:
- Generating and validating JWTs for secure communication.
- Implementing JWT-based authentication and authorization.
- Configuring stateless sessions, token expiration, and refresh logic.

### OAuth 2.0

OAuth 2.0 is a standard for enabling secure access to APIs with third-party integration. This example includes:
- Configuring OAuth 2.0 client and authorization code flows.
- Setting up OAuth 2.0 with Spring Security.
- Securing endpoints based on scopes and permissions.

## Getting Started

To set up the project locally, follow these instructions.

### Prerequisites

- **JDK 21** installed
- **MongoDB** installed and running on your system or hosted remotely
- **Maven** (3.6+) for building and running the project
- Basic knowledge of Spring Boot, Spring Security, and MongoDB

### Installation

1. Clone the repository:
   ```bash
   [git clone https://github.com/your-username/spring-security-programs.git](https://github.com/rebuildMe-123/spring-security.git)
