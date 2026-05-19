# Team Task Manager Full-Stack App

A modern full-stack task and project management platform built using React and Node.js. This application allows teams to manage projects, assign tasks, track progress, and collaborate with role-based access control.

---

# 🚀 Live Demo

## Backend Live URL
https://team-task-manager-full-stack-p04u.onrender.com

---

# 🚀 Features

- User Signup and Login Authentication
- Token-based Authentication System
- Admin and Member Roles
- Role-Based Access Control (RBAC)
- Create and Manage Projects
- Add and Manage Team Members
- Create, Assign, Update, and Delete Tasks
- Task Priority and Due Date Management
- Dashboard Analytics
- Track Completed, Pending, and Overdue Tasks
- REST API Architecture
- File-Based JSON Database
- Responsive Frontend UI

---

# 🛠️ Tech Stack

## Frontend
- React.js
- HTML5
- CSS3
- JavaScript

## Backend
- Node.js
- REST APIs
- Native HTTP Server

## Database
- JSON-based NoSQL-style File Database

## Authentication
- Token-Based Authentication
- Password Hashing

---

# 📂 Project Structure

```bash
team-task-manager-full-stack/
│
├── backend/
│   ├── server.js
│   ├── package.json
│   └── data/
│       └── db.json
│
├── frontend/
│   ├── index.html
│   └── src/
│       ├── app.js
│       └── styles.css
│
├── package.json
├── package-lock.json
└── README.md
```

---

# ⚙️ Installation & Setup

## Clone Repository

```bash
git clone https://github.com/Sudhir104/Team-Task-Manager-Full-Stack.git
```

## Move to Project Folder

```bash
cd Team-Task-Manager-Full-Stack
```

## Install Dependencies

```bash
npm install
```

## Start Application

```bash
npm start
```

---

# 🌐 Run Locally

After starting the server, open:

```bash
http://localhost:5000
```

---

# 🔑 Demo Credentials

The application automatically creates demo users on first run.

| Role | Email | Password |
|------|------|------|
| Admin | admin@example.com | admin123 |
| Member | member@example.com | member123 |

You can also create your own account using the Signup page.

---

# 📊 Dashboard Features

- Total Tasks Overview
- Completed Tasks Tracking
- Pending Tasks Monitoring
- Overdue Tasks Detection
- Project Progress Analytics
- Team Collaboration Tracking

---

# 🔐 Role Permissions

## Admin
- Create Projects
- Add or Remove Team Members
- Create and Assign Tasks
- Update Any Task
- Delete Tasks
- View Complete Dashboard Data

## Member
- View Assigned Tasks
- Update Task Status
- Access Team Projects
- Track Personal Task Progress

---

# 📡 REST API Endpoints

## Authentication

```http
POST /api/auth/signup
POST /api/auth/login
GET  /api/auth/me
```

## Users

```http
GET /api/users
```

## Projects

```http
GET    /api/projects
POST   /api/projects
PATCH  /api/projects/:id/team
```

## Tasks

```http
GET     /api/tasks
POST    /api/tasks
PATCH   /api/tasks/:id/status
DELETE  /api/tasks/:id
```

## Dashboard

```http
GET /api/dashboard
```

---

# 🧠 Application Highlights

- Clean Full-Stack Architecture
- Simple File-Based Data Storage
- Lightweight Backend Without External Database
- Beginner-Friendly MERN-style Project
- Easy Deployment on Render and Vercel
- Designed for Team Collaboration and Productivity

---

# ☁️ Deployment

## Backend Deployment
- Render

## Frontend Deployment
- Vercel

---

# 📌 Future Improvements

- JWT Authentication
- MongoDB Integration
- Real-Time Notifications
- File Upload Support
- Activity Logs
- Team Chat System
- Drag-and-Drop Kanban Board

---

# 👨‍💻 Author

**Sudhir Mathur**

- GitHub: https://github.com/Sudhir104
- LinkedIn: https://www.linkedin.com/in/sudhir-mathur-346b3b268

---

# ⭐ Repository

Repository Link:
https://github.com/Sudhir104/Team-Task-Manager-Full-Stack

---

# 📄 License

This project is licensed under the MIT License.
