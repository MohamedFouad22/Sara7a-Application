# Sara7a Application

A complete backend API for a modern Sara7a-style anonymous messaging platform built with Node.js, Express.js, and MongoDB, designed with secure authentication, user profile management, cloud file uploads, and private messaging functionality.

The project provides a full anonymous messaging experience including authentication, email verification, password recovery, profile management, secure media uploads, account protection, and user-to-user messaging.

---

## 🚀 Tech Stack

### Backend
- Node.js
- Express.js
- JavaScript

### Database
- MongoDB
- Mongoose

### Validation & Security
- Joi Validation
- JWT Authentication
- Password Hashing
- Crypto
- Token Management
- API Security Best Practices

### File Upload & Cloud Storage
- Cloudinary
- Local File Upload System

### Communication
- Nodemailer
- Email Verification System

### Development Tools
- Git
- GitHub
- RESTful API Architecture
- Postman Collection

---

## 📌 Main Modules

The system is organized into three core modules:

---

# 1. Auth Module

Handles the complete authentication lifecycle and account security.

### Features

- User Registration (Signup)
- Login
- Social Media Login (OAuth)
- Email Confirmation
- Forget Password
- Reset Password
- Update Password
- Refresh Token
- Revoke Token
- Secure JWT Authentication

---

# 2. User Module

Manages user profiles, account security, and media uploads.

### Features

- Get Profile
- Update User Profile
- Upload Profile Image
- Upload Cover Image
- Local Upload Support
- Cloud Upload Support (Cloudinary)
- 2-Step Verification
- Freeze Account
- Restore Account
- Get All Users (Admin Access)

---

# 3. Message Module

Provides the core anonymous messaging functionality.

### Features

- Send Message to User
- Get Message History
- Private User Messaging
- Secure Message Flow

---

## ☁️ Cloudinary Integration

The system uses Cloudinary for secure image management:

- Profile Image Upload
- Cover Image Upload
- Cloud Storage Management
- Secure Media Handling

This improves scalability and avoids storing media files directly on the server.

---

## 🔐 Authentication Flow

Authentication is built using:

- Access Token
- Refresh Token
- Email Confirmation
- Password Recovery Flow
- Social Media Login
- 2-Step Verification

This ensures strong account security and production-ready authentication logic.

---

## 📮 Postman Collection

The project includes a complete Postman Collection served at:

```bash
http://localhost:3000/api/v1
