# Full Stack Employee Management System (EMS)

A full-stack Employee Management System built using the MERN Stack (MongoDB, Express.js, React.js, and Node.js). The application provides role-based access for Admins and Employees and includes attendance tracking, leave management, payslip generation, email notifications, and background job scheduling.

## 🚀 Live Demo

Live Application:

https://full-stack-ems-system-mern-kappa.vercel.app/dashboard

## 📂 GitHub Repository

https://github.com/NishantChauhan11/Full-Stack-EMS-System-MERN

---

# 📌 Project Overview

The Employee Management System (EMS) is a real-world full-stack web application designed to simplify employee administration within an organization.

The system enables administrators to manage employees, monitor attendance, process leave requests, generate payslips, and send automated email notifications. Employees can access their profiles, check attendance records, apply for leave, and view payslips.

This project demonstrates practical implementation of modern web development technologies and enterprise-level application architecture.

---

# ✨ Key Features

## Admin Features

* Secure Admin Authentication
* Employee Management (Create, Read, Update, Delete)
* Attendance Monitoring
* Leave Request Approval/Rejection
* Payslip Generation
* Dashboard Analytics
* Email Notifications
* Role-Based Access Control

## Employee Features

* Secure Login System
* Profile Management
* Attendance Tracking
* Leave Application System
* Payslip Access
* Email Notifications

---

# 🛠️ Tech Stack

## Frontend

### React.js

A JavaScript library used for building fast, reusable, and interactive user interfaces.

### Vite

A modern frontend build tool that provides faster development and optimized production builds.

### Tailwind CSS

A utility-first CSS framework used for creating responsive and modern user interfaces efficiently.

### React Router DOM

Used for client-side routing and navigation between pages without full page reloads.

### Axios

A promise-based HTTP client used for communicating with backend APIs.

---

## Backend

### Node.js

A JavaScript runtime environment that allows server-side application development.

### Express.js

A lightweight backend framework used for building RESTful APIs and handling server logic.

### JWT Authentication

Used for secure user authentication and authorization through token-based security.

### Middleware

Used to validate requests, protect routes, and manage application-level security.

---

## Database

### MongoDB Atlas

A cloud-hosted NoSQL database used to store application data securely and efficiently.

### Mongoose

An Object Data Modeling (ODM) library that simplifies MongoDB database operations.

---

## Background Jobs

### Inngest

Used for scheduling background tasks, event-driven workflows, and automated cron jobs.

Examples:

* Scheduled tasks
* Automated processing
* Event-based workflows

---

## Email Service

### Brevo (SMTP)

Used for sending automated emails and notifications to employees and administrators.

Examples:

* Account notifications
* Leave updates
* System alerts

---

# 🏗️ Project Architecture

Frontend (React.js)

⬇

REST API Requests

⬇

Backend (Node.js + Express.js)

⬇

Controllers

⬇

MongoDB Atlas Database

⬇

Response Returned to Frontend

---

# 📁 Project Structure

```text
FullStack-EMS
│
├── client
│   ├── public
│   ├── src
│   ├── package.json
│   └── vite.config.js
│
├── server
│   ├── config
│   ├── constants
│   ├── controllers
│   ├── inngest
│   ├── middleware
│   ├── models
│   ├── routes
│   ├── seed.js
│   ├── server.js
│   └── package.json
│
└── README.md
```

---

# 🔐 Authentication & Authorization

The application uses JWT (JSON Web Tokens) for secure authentication.

### Roles Supported

* Admin
* Employee

Protected routes ensure that only authorized users can access sensitive resources and functionalities.

---

# 📊 Modules Implemented

* Authentication Module
* Employee Management Module
* Attendance Management Module
* Leave Management Module
* Payslip Management Module
* Dashboard Analytics Module
* Email Notification Module
* Background Job Scheduling Module

---

# ⚙️ Installation & Setup

## Prerequisites

* Node.js
* MongoDB Atlas Account
* Brevo Account
* Inngest Account
* Git

---

## Clone Repository

```bash
git clone https://github.com/NishantChauhan11/Full-Stack-EMS-System-MERN.git
```

---

## Setup Server

Navigate to server folder:

```bash
cd server
```

Install dependencies:

```bash
npm install
```

Configure environment variables:

* MongoDB URI
* JWT Secret
* Brevo SMTP Credentials
* Inngest Credentials
* Admin Email

Seed Admin User:

```bash
npm run seed
```

Run Server:

```bash
npm run server
```

---

## Setup Client

Navigate to client folder:

```bash
cd client
```

Install dependencies:

```bash
npm install
```

Run Application:

```bash
npm run dev
```

---

# 🌐 Deployment

## Frontend Deployment

* Vercel

## Backend Deployment

* Vercel

## Database Hosting

* MongoDB Atlas

---

# 🎯 Learning Outcomes

Through this project, I gained practical experience in:

* Full Stack MERN Development
* REST API Development
* Authentication & Authorization
* MongoDB Database Design
* Backend Architecture
* Frontend Component Design
* Email Integration
* Background Job Scheduling
* Cloud Deployment
* Git & GitHub Workflow

---

# 💼 Resume Highlights

* Developed a full-stack Employee Management System using MERN Stack.
* Implemented role-based authentication and authorization.
* Built attendance, leave management, and payslip modules.
* Integrated MongoDB Atlas for cloud database management.
* Configured Inngest for event-driven background workflows.
* Implemented Brevo SMTP service for automated email notifications.
* Deployed frontend and backend applications using Vercel.

---

# 👨‍💻 Author

Nishant Chauhan

B.Tech Computer Science Engineering

Email: [26nishantchauhan@gmail.com](mailto:26nishantchauhan@gmail.com)

GitHub:
https://github.com/NishantChauhan11

---

# 📜 License

This project is intended for educational, learning, and portfolio purposes.
