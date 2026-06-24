# Full Stack Employee Management System (EMS)

A full-stack Employee Management System built using the MERN Stack (MongoDB, Express.js, React.js, and Node.js). The application provides role-based access for Admins and Employees and includes employee management, attendance tracking, leave management, payslip generation, and dashboard analytics.

---

# 🚀 Live Demo

https://full-stack-ems-system-mern-kappa.vercel.app/dashboard

---

# 📂 GitHub Repository

https://github.com/NishantChauhan11/Full-Stack-EMS-System-MERN

---

# 📌 Project Overview

The Employee Management System (EMS) is a full-stack web application designed to simplify employee administration inside an organization.

Administrators can manage employees, monitor attendance, process leave requests, and generate payslips. Employees can log in to their accounts, view their profiles, check attendance records, apply for leave, and access payslips.

This project demonstrates practical implementation of MERN stack technologies and role-based access control.

---

# ✨ Features

## Admin Features

* Secure Admin Authentication
* Employee Management (Create, Read, Update, Delete)
* Attendance Monitoring
* Leave Request Approval and Rejection
* Payslip Generation
* Dashboard Analytics
* Role-Based Access Control

## Employee Features

* Secure Login System
* Profile Management
* Attendance Tracking
* Leave Application System
* Payslip Access

---

# 🛠️ Tech Stack

## Frontend

* React.js
* Vite
* Tailwind CSS
* React Router DOM
* Axios

## Backend

* Node.js
* Express.js
* JWT Authentication
* Middleware

## Database

* MongoDB Atlas
* Mongoose

## Additional Services

* Inngest for background jobs and scheduled tasks
* Brevo SMTP configuration support

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
│   ├── controllers
│   ├── middleware
│   ├── models
│   ├── routes
│   ├── inngest
│   ├── seed.js
│   ├── server.js
│   └── package.json
│
└── README.md
```

---

# 🔐 Authentication & Authorization

The application uses JWT (JSON Web Tokens) for secure authentication and authorization.

### Supported Roles

* Admin
* Employee

Protected routes ensure that only authorized users can access sensitive functionalities.

---

# 📊 Modules Implemented

* Authentication Module
* Employee Management Module
* Attendance Management Module
* Leave Management Module
* Payslip Management Module
* Dashboard Analytics Module

---

# ⚙️ Installation & Setup

## Prerequisites

* Node.js
* MongoDB Atlas Account
* Git

---

## Clone Repository

```bash
git clone https://github.com/NishantChauhan11/Full-Stack-EMS-System-MERN.git
```

---

## Setup Backend

```bash
cd server
npm install
```

Configure environment variables:

* MongoDB URI
* JWT Secret
* Admin Email

Create Admin User:

```bash
npm run seed
```

Run Backend Server:

```bash
npm run server
```

---

## Setup Frontend

```bash
cd client
npm install
npm run dev
```

---

# 🌐 Deployment

## Frontend

* Vercel

## Backend

* Vercel

## Database

* MongoDB Atlas

---

# 🎯 Learning Outcomes

Through this project, I gained practical experience in:

* Full Stack MERN Development
* REST API Development
* Authentication and Authorization
* MongoDB Database Design
* Backend Architecture
* Frontend Component Design
* Cloud Deployment
* Git and GitHub Workflow

---

# 💼 Resume Highlights

* Developed a full-stack Employee Management System using the MERN Stack.
* Implemented role-based authentication and authorization using JWT.
* Built employee, attendance, leave, and payslip management modules.
* Integrated MongoDB Atlas for cloud database management.
* Developed REST APIs using Express.js and Node.js.
* Deployed frontend and backend applications using Vercel.

---

# 📧 Contact

Email: [26nishantchauhan@gmail.com](mailto:26nishantchauhan@gmail.com)
