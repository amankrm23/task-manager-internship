# Task Manager Pro - Full-Stack Application

A responsive, full-stack Task Management web application built with a focus on clean architecture and secure user authentication. This project demonstrates complete CRUD operations, token-based security, and cloud database integration.

## 🚀 Live Demo
* **Frontend (Live Site):** [Insert your Netlify Link Here]
* **Backend API:** [Insert your Render Link Here]

## ✨ Key Features
* **Secure Authentication:** User registration and login protected by JSON Web Tokens (JWT) and bcrypt password hashing.
* **Full CRUD Functionality:** Users can Create, Read, Update, and Delete personal tasks.
* **Task Organization:** Built-in tools to filter tasks by status (Pending, In Progress, Completed) and sort them by creation date.
* **Protected Routes:** Backend API routes are secured so users can only access and modify their own tasks.
* **Responsive UI:** Clean, modern interface that works seamlessly on both desktop and mobile devices.

## 💻 Technology Stack
* **Frontend:** HTML5, CSS3, Vanilla JavaScript
* **Backend:** Node.js, Express.js
* **Database:** MongoDB (Mongoose ODM)
* **Authentication:** JWT (JSON Web Tokens)
* **Deployment:** Netlify (Frontend) & Render (Backend)

## 🛠️ Local Setup Instructions

If you want to run this project locally on your machine, follow these steps:

**1. Clone the repository**
`git clone https://github.com/YOUR-USERNAME/task-manager-internship.git`

**2. Backend Setup**
* Navigate to the backend directory: `cd task-backend`
* Install dependencies: `npm install`
* Create a `.env` file in the backend directory and add:
  * `PORT=5000`
  * `MONGO_URI=your_mongodb_connection_string`
  * `JWT_SECRET=your_secret_key`
* Start the server: `node server.js`

**3. Frontend Setup**
* Navigate to the frontend directory: `cd task-frontend`
* Open `index.html` in your code editor.
* Ensure the `SERVER_URL` on line 105 points to `http://localhost:5000/api`.
* Open `index.html` in your web browser to view the application.
