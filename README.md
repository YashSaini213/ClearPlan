# ✅ ClearPlan — Task Management Platform

<p align="center">
  <img src="https://raw.githubusercontent.com/halfrost/halfrost/master/icons/header_1.png" alt="banner" width="100%">
</p>

<h1 align="center">ClearPlan</h1>

<p align="center">
  A full-stack task management web application built with the MERN stack.
</p>

<p align="center">
  <a href="https://github.com/YashSaini213/ClearPlan">
    <img src="https://img.shields.io/badge/GitHub-Repository-black?style=for-the-badge&logo=github" alt="GitHub">
  </a>
</p>

---

## 📌 About The Project

**ClearPlan** is a full-stack task management application designed to help users organize, manage, and track their daily tasks efficiently.

The platform allows users to create tasks, assign priorities and deadlines, update task information, and delete completed or unnecessary tasks through a simple and intuitive interface.

The application is built using the **MERN stack — MongoDB, Express.js, React.js, and Node.js**.

---

## ✨ Features

### 👤 User Features

- 🔐 User authentication
- ➕ Create new tasks
- ✏️ Update existing tasks
- 🗑️ Delete tasks
- 📋 View and manage tasks
- 🎯 Set task priorities
- 📅 Add task deadlines
- 📊 Track daily tasks
- 📱 Responsive user interface

### 📋 Task Management

- 📝 Create and organize tasks
- 🚨 Set task priority
- ⏰ Set deadlines
- 🔄 Update task details
- ❌ Delete tasks
- 📌 Track task status
- ⚡ Simple and intuitive task management

---

## 🛠️ Tech Stack

### Frontend

<p>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" width="50" height="50" alt="React">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" width="50" height="50" alt="JavaScript">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" width="50" height="50" alt="HTML5">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" width="50" height="50" alt="CSS3">
</p>

- React.js
- JavaScript
- HTML5
- CSS3
- Vite
- Axios
- React Router

### Backend

<p>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" width="50" height="50" alt="Node.js">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" width="50" height="50" alt="Express.js">
</p>

- Node.js
- Express.js
- REST APIs
- JavaScript

### Database

<p>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" width="50" height="50" alt="MongoDB">
</p>

- MongoDB
- Mongoose
- MongoDB Atlas

### Tools

- Git & GitHub
- VS Code
- Postman
- Vite
- MongoDB Atlas
- npm

---

## 📂 Project Structure

```text
ClearPlan/
│
├── config/
│   └── database configuration
│
├── controllers/
│   └── application controllers
│
├── middleware/
│   └── authentication & middleware
│
├── models/
│   └── MongoDB models
│
├── public/
│   └── static assets
│
├── routes/
│   └── API routes
│
├── src/
│   ├── components/
│   ├── pages/
│   ├── assets/
│   └── application files
│
├── uploads/
│   └── uploaded files
│
├── package.json
├── package-lock.json
├── vite.config.js
├── index.html
└── README.md
```

The repository currently contains directories including `config`, `controllers`, `middleware`, `models`, `routes`, `src`, `public`, and `uploads`, along with the Vite configuration and package files.

---

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/YashSaini213/ClearPlan.git
```

### 2. Navigate into the project

```bash
cd ClearPlan
```

### 3. Install dependencies

```bash
npm install
```

---

## 🔐 Environment Variables

Create a `.env` file in the project root and add the required environment variables.

Example:

```env
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

> ⚠️ Never commit your `.env` file to GitHub.

Add the following to `.gitignore`:

```gitignore
node_modules/
.env
.env.*
!.env.example
```

---

## ▶️ Running the Application

Start the development server using:

```bash
npm run dev
```

The Vite development server will provide the local URL in your terminal.

Typically:

```text
http://localhost:5173
```

---

## 🔄 Application Workflow

```text
                 ┌─────────────────┐
                 │      User       │
                 └────────┬────────┘
                          │
                          ▼
                 ┌─────────────────┐
                 │ React Frontend  │
                 │     + Vite      │
                 └────────┬────────┘
                          │
                          ▼
                 ┌─────────────────┐
                 │  Express API    │
                 │     Server      │
                 └────────┬────────┘
                          │
                          ▼
                 ┌─────────────────┐
                 │    MongoDB      │
                 │    Database     │
                 └─────────────────┘
```

---

## 🔐 Authentication

ClearPlan uses authentication and protected backend functionality to provide users with a secure task-management experience.

Key concepts include:

- 🔐 User authentication
- 🛡️ Protected routes
- 🔑 Secure session/token handling
- 👤 User-specific task management
- 🔒 Backend API protection

---

## 📋 Task Management

ClearPlan focuses on making everyday task management simple and organized.

Users can:

- ➕ Create tasks
- ✏️ Edit tasks
- 🗑️ Delete tasks
- 📅 Assign deadlines
- 🚨 Set priorities
- 📋 Track daily tasks
- 🔄 Update task information

This allows users to keep their daily work organized in one place.

---

## 🚀 Future Improvements

- 📊 Advanced task analytics
- 📅 Calendar integration
- 🔔 Task reminders and notifications
- 🏷️ Task categories and tags
- 🔎 Advanced task search and filtering
- 🌙 Dark mode
- 📱 Mobile application
- 👥 Team collaboration
- 📈 Productivity analytics
- 🔄 Drag-and-drop task management

---

## 🌐 Live Demo

The project is deployed and available online:

**ClearPlan:**  
https://clear-plan.vercel.app/

The repository currently lists the ClearPlan Vercel deployment as its live project link.

---

## 👨‍💻 Developer

**Yashraj Saini**

Full-Stack Developer | MERN | React | Node.js

📍 Jaipur, India

- 💼 LinkedIn: [Yashraj Saini](https://www.linkedin.com/in/yashraj-saini-0aa230214/)
- 💻 GitHub: [YashSaini213](https://github.com/YashSaini213)
- 🌐 Portfolio: [My Portfolio](https://my-portfolio-zeta-murex-12.vercel.app/)
- 📧 Email: yashrajsaini713@gmail.com

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

Thanks for checking out **ClearPlan!** 🚀
