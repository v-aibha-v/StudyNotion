# StudyNotion - EdTech Platform 🚀

![Main Page](images/mainpage.png)

StudyNotion is a fully functional **EdTech Platform** built using the **MERN Stack (MongoDB, Express.js, React.js, Node.js)**. The platform enables students to create, consume, and rate educational content while allowing instructors to manage and publish courses efficiently.

---

# Table of Contents

- [Introduction](#introduction)
- [System Architecture](#system-architecture)
  - [Front-end](#front-end)
  - [Back-end](#back-end)
  - [Database](#database)
  - [Architecture Diagram](#architecture-diagram)
- [API Design](#api-design)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)

---

# Introduction

StudyNotion provides an interactive learning platform where students can browse, purchase, and consume courses while instructors can create and manage educational content. The platform includes authentication, payment integration, media management, and course management features.

---

# System Architecture

The platform follows a **Client-Server Architecture** consisting of:

- Front-end
- Back-end
- Database

The frontend communicates with the backend using REST APIs, while the backend manages authentication, business logic, and database operations.

---

## Front-end

The frontend is built using **ReactJS** and **Tailwind CSS** to provide a responsive and interactive user experience.

### Student Features

- Homepage
- Course Listing
- Wishlist
- Cart Checkout
- Course Content
- User Profile
- Edit Profile

### Instructor Features

- Dashboard
- Insights
- Create Courses
- Update Courses
- Delete Courses
- Manage Course Content
- Profile Management

---

## Back-end

The backend is developed using **Node.js** and **Express.js**.

### Features

- User Authentication & Authorization
- OTP Verification
- Forgot Password
- JWT Authentication
- Course Management
- Razorpay Payment Integration
- Cloudinary Media Upload
- Student Enrollment
- Instructor Dashboard APIs

---

## Database

MongoDB is used as the primary database for storing:

- User Information
- Courses
- Categories
- Sections
- Subsections
- Ratings & Reviews
- Payments

---

## Database Schema

![Database Schema](images/schema.png)

---

## Architecture Diagram

![Architecture](images/architecture.png)

---

# API Design

The backend follows REST architecture and uses standard HTTP methods:

- GET
- POST
- PUT
- DELETE

Data exchange is performed using JSON.

---

# Installation

1. Clone the repository

```bash
git clone https://github.com/v-aibha-v/StudyNotion.git
```

2. Navigate to the project directory

```bash
cd StudyNotion
```

3. Install dependencies

```bash
npm install
```

---

# Configuration

Create a `.env` file and add the following environment variables:

```env
PORT=4000

MONGODB_URL=<your-mongodb-connection-url>

JWT_SECRET=<your-jwt-secret-key>

MAIL_HOST=smtp.gmail.com
MAIL_PORT=587
MAIL_USER=<your-email>

MAIL_PASS=<your-app-password>

CLOUD_NAME=<your-cloudinary-cloud-name>

API_KEY=<your-cloudinary-api-key>

API_SECRET=<your-cloudinary-api-secret>

RAZORPAY_KEY=<your-razorpay-key-id>

RAZORPAY_SECRET=<your-razorpay-secret>

FOLDER_NAME=StudyNotion

FRONTEND_URL=http://localhost:3000
```

---

# Usage

Start the backend server:

```bash
npm run server
```

Start the frontend:

```bash
npm start
```

Open your browser and visit:

```
http://localhost:3000
```

---

# Tech Stack

- React.js
- Node.js
- Express.js
- MongoDB
- Redux
- Tailwind CSS
- JWT
- Bcrypt
- Cloudinary
- Razorpay
- Nodemailer

---

# Screenshots

## Home Page

![Main Page](images/mainpage.png)

## Database Schema

![Database Schema](images/schema.png)

## Architecture Diagram

![Architecture](images/architecture.png)

---

# Author

**Vaibhav**

GitHub Repository: https://github.com/v-aibha-v/StudyNotion