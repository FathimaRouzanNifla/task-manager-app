
# Task Manager Web Application (MERN Stack)

## Overview
This is a full-stack Task Manager app built with the MERN stack (MongoDB, Express, React, Node.js).  
Users can register, login, and manage their personal tasks with features like creating, editing, deleting, marking complete, filtering, sorting, and pagination.

## Live Demo
- Frontend:(https://mytaskdesk.netlify.app)  
- Backend API:(https://task-manager-backend-production-9c2d.up.railway.app)

## Features
- User Authentication (JWT)
- Task CRUD (Create, Read, Update, Delete)
- Mark tasks as Completed or Pending
- Filter tasks by Priority and Status
- Sort tasks by Due Date or Priority
- Pagination for better task list performance
- Responsive UI built with Tailwind CSS

## Tech Stack
- Frontend: React, Tailwind CSS, Axios, React Router
- Backend: Node.js, Express.js, MongoDB Atlas, Mongoose
- Deployment: Vercel or Netlify (Frontend), Railway or Fly.io (Backend)

---

## Project Setup Instructions

### Backend Setup
1. Navigate to backend folder:
   ```bash
   cd backend
## Install dependencies:
npm install

## Ensure API base URL is set (in .env or directly in code):


REACT_APP_API_URL=http://localhost:5001

## Start frontend app:

npm start
Open your browser to http://localhost:3000 to view the app.



## Postman Collection
The Postman collection containing all API endpoints is included in this repo under:

docs/TaskManager.postman_collection.json

Import it into Postman to test all endpoints with example requests.

## Deployment
## Backend Deployed on Railway
Make sure environment variables are set correctly (MongoDB URI, JWT secret, etc.)

## Frontend
## Deployed on Netlify
Make sure the frontend is configured to use the deployed backend URL (REACT_APP_API_URL).
##  Screenshots

### Login Page
![Login Page](./screenshots/login-page.png)

### Dashboard
![Dashboard](./screenshots/dashboard.png)

### Add New Task
![Add New](./screenshots/add-new.png)

### Create Task Form
![Create](./screenshots/create.png)

### Edit Task
![Edit Task](./screenshots/edit-task.png)

### Task List View
![Task List](./screenshots/task.png)

### User Account
![Account](./screenshots/account.png)

### Filter by Priority
![Filter Priority](./screenshots/filter-priority.png)

### Sort by Due Date
![Filter Sort By](./screenshots/filter-shortby.png)

### Filter Tasks
![Filter Task](./screenshots/filter-task.png)

##  Demo Video
![Download Demo Video](./demovideo/video2679587306.mp4)


Notes
Feel free to reach out if you want a walkthrough or have any questions.

Thank you for reviewing my project!
