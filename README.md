# RBAC

This project implements a secure Role-Based Access Control (RBAC) system using Spring Boot, ensuring authenticated and authorized access to resources based on user roles. It leverages JWT (JSON Web Tokens) for stateless authentication and Spring Security for robust authorization.

User Authentication: Secure user registration and login with hashed passwords (BCrypt).
JWT Integration: Stateless session management using JWT for secure and scalable communication.
Role-Based Authorization: Predefined roles (Admin, Moderator, User) with specific permissions to access resources.
Secure Endpoints: Protect API routes based on roles using Spring Security annotations.
Extensible Architecture: Easily extendable for more roles or permissions as needed.
