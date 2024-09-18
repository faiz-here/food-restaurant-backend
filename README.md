Food-Restaurant App Backend
This project is a backend API for a food-restaurant application. It allows users to create profiles, log in, update their passwords, and delete their profiles/accounts. The app uses MongoDB Atlas for data storage, bcrypt for password hashing, and JWT (JSON Web Tokens) for authentication.

Features
User Registration: Create a user profile with a username, email, and password.
Login: Authenticate users with their email and password, returning a JWT for session management.
Password Update: Users can update their password after logging in.
Profile Deletion: Users can delete their account if they choose.
Password Hashing: Passwords are securely stored using bcrypt hashing.
JWT Authentication: JWT tokens are used to authenticate users and protect routes.
Tech Stack
Node.js: Backend runtime environment
Express.js: Web framework for building REST APIs
MongoDB Atlas: Cloud-based NoSQL database
Mongoose: ODM for MongoDB and Node.js
bcrypt: Library for hashing passwords
JWT (jsonwebtoken): For generating and verifying tokens for user sessions
Prerequisites
Node.js (v14 or higher)
MongoDB Atlas account and cluster
MongoDB Compass and Postman for local testing
