# 🚀 TaskPro – MERN SaaS Task Management (Backend API)

TaskPro Backend is a production-ready RESTful API built using Node.js, Express.js, and MongoDB.  
It provides secure JWT-based authentication, protected routes, and complete task management functionality.

---

## 🌐 Live API

Backend API: https://your-backend-url.onrender.com

---

## 🛠 Tech Stack

- Node.js
- Express.js
- MongoDB (Atlas)
- Mongoose
- JWT (Authentication)
- bcrypt (Password Hashing)
- CORS
- dotenv
- node-cron (Scheduled jobs)
- Render (Deployment)

---

## ✨ Features

- 🔐 User Registration & Login
- 🔑 JWT Authentication
- 🔒 Protected Routes Middleware
- ➕ Create Tasks
- 📄 Read Tasks
- ✏ Update Tasks
- ❌ Delete Tasks
- ✅ Mark Tasks as Completed
- 📊 Task Status Management
- ☁ Cloud Deployment Ready

---

## 📁 Project Structure
backend/
├── config/
├── controllers/
├── middleware/
├── models/
├── routes/
├── server.js
├── package.json
└── .env

⚠ Do not commit `.env` to GitHub.

---
MONGO_URI=your_mongodb_atlas_uri

## 📦 Installation (Local Setup)

Clone repository:

```bash
git clone https://github.com/your-username/fullstack-MERN-backend.git
cd fullstack-MERN-backend

Install dependencies:
--------------------

npm install

Run server:
-------------

npm run dev

or

node server.js
