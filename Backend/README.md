# 🚀 Job Listing Platform (Full-Stack)

A full-stack job listing platform built using **Node.js (Express)** and **MySQL**, designed with a modular REST API architecture. The system supports secure authentication, role-based access control, and advanced job management features.

---

## 🧠 Overview

This application enables employers to create and manage job listings while allowing job seekers to explore, interact, and apply for jobs. The platform emphasizes **secure access**, **scalable backend design**, and **real-world system features**.

---

## 🏗️ System Architecture

```
Client (ReactJs )
        ↓
Node.js (Express REST API)
        ↓
MySQL Database
        ↓
SMTP Email Service (Verification & Password Reset)
```

---

## 🔐 Authentication & Security

* JWT-based authentication
* Role-based authorization (Admin, Employer, Job Seeker)
* Email verification with expiring token
* Secure password reset via email (SMTP)
* Protected routes using middleware

---

## 👥 User Management

* User registration & login
* Profile retrieval and updates
* Admin-level user management (view, update, delete users)

---

## 💼 Job Management

* Create, update, delete job listings (Employer only)
* View all job listings
* Search, filter, and sort jobs
* Pagination for large datasets
* Job categorization (category, location, expiry, status)

---

## ⭐ Interactive Features

* Bookmark jobs
* Rate job listings
* Comment on job posts
* Job recommendation system

---

## 🖼️ Media Handling

* Upload job-related images
* Update and delete uploaded media

---

## ⚙️ API Design

* RESTful API structure
* Modular architecture (routes, controllers, middleware)
* JSON-based request/response handling
* Centralized error handling

---

## 🧪 Key Features

* Scalable backend design using Express.js
* Secure authentication using JWT
* Role-based access control
* Email-based verification and password reset
* Advanced job filtering and searching
* Clean API structure for frontend integration

---

## 🛠️ Tech Stack

* **Backend:** Node.js, Express.js
* **Database:** MySQL
* **Authentication:** JSON Web Tokens (JWT)
* **Email Service:** SMTP (NodeMailer)
* **Frontend (separate):** React / Flutter

---

## 📌 API Sample Endpoints

```
POST   /api/auth/register
POST   /api/auth/login
GET    /api/users/profile
PUT    /api/users/:id
DELETE /api/users/:id

POST   /api/jobs
GET    /api/jobs
GET    /api/jobs/:id
PUT    /api/jobs/:id
DELETE /api/jobs/:id
```

---

## 🚀 Getting Started

### 1. Clone the repository

```
git clone https://github.com/SuneraR/Job-listing-website.git
cd backend
cd frontend
```

### 2. Install dependencies

```
npm install
```

### 3. Configure environment variables

Create a `.env` file and configure:

```
PORT=5000
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=yourpassword
DB_NAME=job_portal

JWT_SECRET=your_secret_key

EMAIL_USER=your_email
EMAIL_PASS=your_email_password
```

### 4. Run the server

```
npm start
```

---

## 📈 Future Improvements

* Microservices architecture (separate services for auth, jobs, etc.)
* Integration with external APIs (e.g., payment, job providers)
* Docker containerization
* CI/CD pipeline

---

## 🤝 Contribution

Contributions are welcome! Feel free to fork this repository and submit pull requests.

---

## 📄 License

This project is open-source and available under the MIT License.

---


