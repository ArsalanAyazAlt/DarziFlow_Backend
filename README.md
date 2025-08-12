# DarziFlow Backend

DarziFlow is a **garment production management system** designed to streamline collaboration between clients, supervisors, QC officers, and admins in the textile industry.  
This repository contains the **backend API** for DarziFlow, built with **Node.js, Express, MongoDB, and JWT** authentication.  

The backend is designed with **role-based access control (RBAC)** to support multiple user roles:
- Moderator (platform owners with full system control)
- Admin (manages departments, orders, and supervisors)
- Supervisor (manages production stages and daily wage workers)
- QC Officer (quality verification at each stage)
- Client (order tracking and feedback)

---

## 🚀 Features

- Secure **JWT-based authentication** and **role-based access control**
- Scalable architecture for adding new roles and modules
- Seeded **Moderator accounts** for initial platform setup
- User management (add, edit, delete, assign roles)
- Secure password hashing with **bcrypt**
- API security best practices with **Helmet**, **CORS**, and **rate limiting**
- MongoDB connection via **Mongoose**

---

## 🛠 Tech Stack

- **Node.js** – Backend runtime
- **Express.js** – API framework
- **MongoDB + Mongoose** – Database and ORM
- **JWT (JSON Web Token)** – Authentication
- **Bcrypt.js** – Password hashing
- **Helmet, CORS, Morgan** – Security and logging

---

## 📂 Project Structure
