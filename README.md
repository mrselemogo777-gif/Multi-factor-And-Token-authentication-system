🔐 Multi-factor And Token Authentication System

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Flask](https://img.shields.io/badge/Flask-2.0+-green.svg)](https://flask.palletsprojects.com/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Security](https://img.shields.io/badge/Security-Auth-red.svg)](https://github.com/mrselemogo777-gif)

Multi-factor And Token Authentication System is a secure Flask-based authentication solution featuring OTP verification, token-based API authentication, and comprehensive security measures.

**Developed as part of Advanced Cybersecurity Development **

---
🎥 Demo Video

[![Watch the Demo](https://img.youtube.com/vi/RJ63vy679B4/0.jpg)](https://youtu.be/RJ63vy679B4)

*Click the thumbnail to watch the demo on YouTube*
---

## 📋 Project Overview

This authentication system demonstrates secure implementation of modern authentication protocols:

- **Password-based authentication** with bcrypt hashing
- **OTP (One-Time Password)** verification via email
- **Token-based authentication** for API endpoints
- **Secure session management**
- **SQL injection protection** (parameterized queries)
- **Cross-Site Scripting (XSS) prevention**

The application follows a modular Flask architecture for maintainability and security best practices.

---

## 🔑 Core Features

### User Authentication
- User registration & login with validation
- Strong password hashing using bcrypt (12 rounds)
- Duplicate email/username prevention
- Input validation and error feedback

### OTP Verification
- Time-based One-Time Password (TOTP)
- 30-second validity window
- Email delivery via SMTP
- Resend functionality after timeout

### Token Authentication (API)
- JWT-based token generation and validation
- Token expiration (15 minutes)
- Refresh token support
- Protected API endpoints with role-based access

### Security Features
- **bcrypt** password hashing (industry standard)
- **Parameterized queries** (prevents SQL injection)
- **Input sanitization** (prevents XSS)
- **Rate limiting** on OTP requests
- **Session expiry** after inactivity
- **Secure cookie** configuration
- **CSRF tokens** on forms

---

## 🛠️ Technology Stack

| Technology | Purpose |
|------------|---------|
| **Python 3.8+** | Core programming language |
| **Flask** | Web framework |
| **Flask-SQLAlchemy** | Database ORM |
| **bcrypt** | Password hashing |
| **pyotp** | OTP generation/verification |
| **MySQL / SQLite** | Database |
| **Bootstrap 5** | Frontend styling |
| **JWT** | Token-based authentication |

---
