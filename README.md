# 🔐 React Routing – Dynamic & Protected Routes

## 📌 Overview
This project demonstrates dynamic routing and protected routes in React
using React Router, localStorage-based authentication, and API data fetching.

---

## 🎯 Objectives
- Implement protected routes
- Use dynamic routing with URL parameters
- Manage authentication using localStorage
- Fetch and display API data
- Redirect users based on auth state

---

## 🧩 Routes Overview

| Route | Access | Description |
|------|-------|-------------|
| / | Public | Home Page |
| /login | Public | Login Page |
| /todos | Protected | Todos List |
| /todos/:todoId | Protected | Todo Details |

---

## 🗂 Folder Structure

src/

├── components/

│ ├── Home.jsx

│ ├── Login.jsx

│ ├── Todos.jsx

│ ├── TodoDetails.jsx

│ ├── ProtectedRoute.jsx

├── App.js

├── index.js

└── App.css

---

## 🔐 Authentication Logic
- Credentials:
  - Email: admin@gmail.com
  - Password: admin@123
- On successful login:
  - `isLoggedIn = true` stored in localStorage
- Unauthorized users are redirected to `/login`

---

## 🧠 Key Concepts Used
- BrowserRouter
- Routes & Route
- Navigate
- useParams
- localStorage
- Dynamic routes
- Protected routes

---

## 🎓 Learning Outcomes
- Route protection in React
- Authentication-based navigation
- Real-world routing patterns
- SPA behavior without page reloads

---

⭐ Feel free to star this repository if you find it helpful!
