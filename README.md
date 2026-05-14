# 🚖 Cab Booking Application (MERN Stack)

## 📌 Project Overview

This project is a full-stack Cab Booking Application developed using the MERN Stack (MongoDB, Express.js, React.js, and Node.js). The application allows users to book cabs online and enables administrators to efficiently manage cars, users, and bookings through a dedicated admin dashboard.

The project is divided into two major parts:

---

# 🖥️ Backend (Node.js + Express.js)

The backend server is developed using Express.js and runs on port `8000`. MongoDB is used as the database with Mongoose ODM for database management.

## Backend Features
- User Authentication (Login & Signup)
- Admin Authentication
- Car Management System
  - Add Cars
  - Edit Cars
  - View Car Listings
- Booking Management
  - Create Bookings
  - View Bookings
- File Upload Support using Multer
  - Upload car images
- REST API Endpoints for:
  - Users
  - Admins
  - Cars
  - Bookings
- CORS Configuration for frontend-backend communication

## Backend Technologies
- Node.js
- Express.js
- MongoDB
- Mongoose
- Multer
- CORS

---

# 💻 Frontend (React.js)

The frontend is built using React 18 with React Router for seamless navigation and Bootstrap for responsive UI design.

## Frontend Features

### 👤 User Module
- User Registration
- User Login
- Book Cabs
- View Booking History
- Home Page

### 🛠️ Admin Module
- Admin Login
- Manage Users
- Add/Edit Cars
- View Bookings

### 🌍 Additional Features
- Google Maps Integration
  - Location Services
  - Cab Selection
- Responsive Mobile-Friendly Design
- Modular Component Structure
  - Admin Components
  - User Components
  - Shared Components

## Frontend Technologies
- React.js
- React Router DOM
- Axios
- Bootstrap
- React Bootstrap
- React Google Maps API

---

# 🗄️ Database

MongoDB is used as the primary database for storing:
- User Details
- Admin Data
- Car Information
- Booking Records

A local MongoDB instance is required to run the project successfully.

---

# ✨ Overall Functionality

The application provides a complete cab booking experience where users can:
- Register and Login
- View available cabs
- Select locations using maps
- Book rides
- Track booking details

Administrators can:
- Manage the cab fleet
- Manage users
- Monitor bookings
- Maintain the overall system through the admin dashboard

This project demonstrates full-stack web development concepts including authentication, CRUD operations, REST APIs, file uploads, responsive UI design, and third-party API integration.
