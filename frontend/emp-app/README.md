<<<<<<< HEAD
"# EmployeeManagementApp" 
=======
# 🧑‍💼 Employee Management System

## 📌 Task-02 – Web Application for Employee Management

This project is an **Employee Management System** that enables administrators to perform full **CRUD operations** (Create, Read, Update, Delete) on employee records. The system includes proper validation and authentication to ensure sensitive employee data is protected.

---

## 🚀 Features

### ✅ Core Functionalities
- ➕ Add New Employee
- 📄 View All Employees
- ✏️ Edit Employee Details
- ❌ Delete Employee
- 🔐 Secure Login for Admins

### 🔐 Security & Validation
- ✅ Form Validation for All Fields
- 🛡️ JWT-based Authentication
- 🔒 Protected Routes for Admin Access

---

## 🛠️ Tech Stack

### Frontend:
- ⚛️ React.js / HTML5 / tailwindcss / Bootstrap
- 🔄 Axios for API requests

### Backend:
- 🟢 Node.js
- 📦 Express.js
- 🧰 bcrypt for password hashing
- 🛡️ JSON Web Token (JWT) for authentication

### Database:
- 🍃 MongoDB (using Mongoose ODM

## 📁 Project Structure

```bash
├── frontend/                  # Frontend Code (React or HTML)
│   ├── src/
│   └── ...
├── backend/                  # Backend Code (Node + Express)
│   ├── models/
│   ├── controllers/
│   ├── routes/
│   └── ...
├── .env
├── package.json
└── README.md

# Clone the repo
git clone https://github.com/your-username/employee-management-system.git

# Install backend dependencies
cd backend
npm install

# Install frontend dependencies
cd ../frontend
npm install

# Start backend server
cd backend
npm run dev

# Start frontend
cd ../frontend
npm start
