# Secure-PHP-Authentication-System
This repository contains a secure PHP authentication system that includes a register page, login page, and an index page. The system ensures protection against SQL injection and provides basic functionality for user registration, authentication, and session management.

Features
User Registration: Allows users to create an account with secure password hashing.
User Login: Authenticates users securely using session management.
Index Page: A home page that requires authentication to access.
SQL Injection Protection: All queries are protected from SQL injection using prepared statements.
Password Hashing: User passwords are hashed using PHP’s password_hash() to ensure secure storage.
Prerequisites
A web server with PHP support (e.g., Apache, Nginx).
A MySQL database.
