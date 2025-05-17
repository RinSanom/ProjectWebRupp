# 🧑‍💼 Employee Management System

A **full-stack web application** that allows users to manage employee records efficiently — built to demonstrate full-stack development, API integration, and modern state management.

> **Features**: View | Search | Add | Edit | Delete  
> **Stack**: React | Laravel | PostgreSQL | Redux Toolkit

---

## 📸 Preview

> *(You can add screenshots or screen recordings here later)*

---

## ✨ Features

✅ Paginated and searchable employee table  
✅ Add new employees with form validation  
✅ Edit existing employee details  
✅ Delete employees with confirmation prompt  
✅ Live UI updates using Redux Toolkit Query  
✅ Toast notifications for all actions (Add/Edit/Delete)

---

## 🛠️ Tech Stack

| Layer        | Technologies Used                                 |
|--------------|----------------------------------------------------|
| **Frontend** | React, Tailwind CSS, React Router                  |
| **State**    | Redux Toolkit, Redux Toolkit Query                 |
| **Backend**  | Laravel (PHP Framework, RESTful API)               |
| **Database** | PostgreSQL                                         |
| **Notifications** | react-toastify                              |

---

## 🧱 Architecture Overview

This application follows a **modular full-stack architecture**:

- The **frontend** (React) communicates with the **backend** (Laravel) via RESTful APIs.
- **Redux Toolkit Query** handles efficient data fetching, caching, and real-time UI updates.
- **Laravel** exposes secured endpoints to perform CRUD operations.
- **PostgreSQL** stores all employee-related data persistently.

---

## 🎯 Purpose

This project was built to:

- Enhance my full-stack development skills.
- Practice Laravel API development and React integration.
- Simulate an internal HR tool used in real-world companies.
- Understand modern state management with Redux Toolkit Query.

---

## 🎨 UI Note

> _“Sorry teacher for the simple UI — I’m a developer, not a designer. I focused more on building the backend and functionality. I’ll work to improve my UI/UX design skills in the future. Thank you for understanding!”_

---

## ⚙️ Installation & Setup

### 📁 1. Clone the Repository

```bash
git clone https://github.com/your-username/employee-management-system.git
cd employee-management-system
```
### 💻 2. Frontend Setup (React)

```bash
cd frontend
npm install
npm run dev
```
### 🖥️ 3. Backend Setup (Laravel)

```baah
cd ../backend
composer install
php artisan key:generate
php artisan migrate
php artisan serve


