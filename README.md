# 🎓 Academic Progress Management System

A comprehensive web-based application to manage academic data, student progress, and faculty activities in an educational institution. Built using **Flask**, **MySQL**, and **HTML templates**, this system supports role-based access for **Admins**, **Teachers**, and **Students**.

## 🚀 Features

### 🧑‍🎓 Student Module
- Secure registration & login
- View all enrolled courses
- Track marks (CA1, CA2, Final Exam)
- Get auto-calculated total performance
- Organized semester-wise mark display

### 👩‍🏫 Teacher Module
- Login and access assigned courses
- Enter/update marks (CA1, CA2, Final)
- View class performance dashboard with averages
- Track student progress and performance trends

### 👨‍💼 Admin Module
- Full CRUD access for:
  - Students, Teachers, Classes, Degrees, Batches, Departments, Courses
- Assign teachers to courses
- Monitor overall academic data in an integrated dashboard
- Auto-generate course codes

## 🛠️ Tech Stack

| Component        | Technology        |
|------------------|-------------------|
| Backend          | Flask (Python)    |
| Database         | MySQL             |
| ORM              | MySQLdb (Flask-MySQLdb) |
| Frontend         | HTML Templates (Jinja2) |
| Authentication   | Session-based     |

## 📦 Installation & Setup

### 🔧 Prerequisites
- Python 3.x
- MySQL server
- pip (Python package installer)

