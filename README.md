# Secure Vault

## Overview

Secure Vault is a full-stack web application designed to securely store and manage sensitive credentials such as passwords, API keys, server credentials, and confidential notes. The application encrypts sensitive information before storing it in the database and ensures that only authorized users can access or decrypt their data.

The project follows modern software engineering practices by combining secure authentication, role-based authorization, strong encryption, clean architecture, and a responsive user interface.

---

## Features

* Secure user authentication
* Role-based access control
* Secure credential management
* End-to-end encryption of sensitive information
* Per-user Data Encryption Keys (DEKs)
* Credential sharing
* Dashboard with cached statistics
* RESTful API
* Responsive user interface

---

## Technology Stack

### Backend

* Laravel
* PHP
* Laravel Sanctum
* Spatie Laravel Permission
* Redis
* OpenSSL (AES-256-GCM)

### Frontend

* React.js
* Vite
* JavaScript (ES6+)
* HTML5
* CSS3
* Tailwind CSS
* Axios
* React Router

### Database

* MySQL

### Development Tools

* Git
* GitHub
* Composer
* npm
* Postman
* Visual Studio Code

---

## Security

The application implements several security best practices, including:

* Authentication using Laravel Sanctum
* Role and permission-based authorization
* Per-user encryption keys
* AES-256-GCM encryption
* Encrypted storage of Data Encryption Keys
* Form Request validation
* Authorization Policies
* Protection against unauthorized access
* Secure password hashing
* Protection against mass assignment vulnerabilities

---

## System Architecture

```text
React.js Frontend
        │
        ▼
REST API
        │
        ▼
Laravel Backend
        │
        ├── Authentication
        ├── Authorization
        ├── Business Logic
        ├── Encryption Services
        ├── Redis Cache
        │
        ▼
MySQL Database
```

---

## Installation

```bash
git clone https://github.com/yourusername/secure-vault.git

cd secure-vault

composer install

npm install

cp .env.example .env

php artisan key:generate

php artisan migrate

npm run dev

php artisan serve
```

---

## Future Enhancements

* Two-Factor Authentication (2FA)
* Email Notifications
* Audit Logs
* Docker Support
* Automated Testing
* CI/CD Pipeline
* Password Generator
* Password Strength Analysis
* Secure File Storage

---


