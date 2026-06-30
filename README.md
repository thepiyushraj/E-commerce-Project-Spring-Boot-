# E-commerce-Project-Spring-Boot-
A full-stack E-Commerce web application built with Spring Boot, JPA, MySQL &amp; JWT authentication — supports product management, cart, orders &amp; dummy payments.
# 🛒 E-Commerce Platform

A full-stack **E-Commerce Web Application** built with **Spring Boot**, **JPA/Hibernate**, **MySQL**, and a **HTML/CSS/JavaScript** frontend. The application supports user authentication using **JWT**, role-based access (Customer/Admin), product & cart management, order placement, and a dummy payment flow.

---

## 📌 Table of Contents
- [About the Project](#-about-the-project)
- [Tech Stack](#-tech-stack)
- [Features](#-features)
- [Project Architecture](#-project-architecture)
- [Folder Structure](#-folder-structure)
- [Database Schema](#-database-schema)
- [Getting Started](#-getting-started)
- [API Endpoints](#-api-endpoints)
- [Future Enhancements](#-future-enhancements)
- [Author](#-author)

---

## 📖 About the Project

This is a backend-heavy **E-Commerce Platform** simulating a real online shopping experience. It includes user registration & login (with JWT-based security), product browsing, cart management, order placement, and a dummy payment integration. The project follows a clean **layered architecture** (Controller → Service → Repository → Database) for scalability and maintainability.

---

## ## 🛠 Tech Stack

| Layer               | Technology                      |
| ------------------- | ------------------------------- |
| **Language**        | Java 17                         |
| **Framework**       | Spring Boot 4.0.6               |
| **ORM**             | Spring Data JPA + Hibernate     |
| **Database**        | MySQL                           |
| **Security**        | Spring Security + JWT           |
| **Payment Gateway** | Stripe API 💳                   |
| **Web Layer**       | Embedded Tomcat                 |
| **Frontend**        | HTML5, CSS3, JavaScript         |
| **Build Tool**      | Maven                           |
| **API Testing**     | Postman                         |
| **Version Control** | Git & GitHub                    |
| **IDE**             | VS Code         |


---

## ✨ Features

### 👤 User Module
- User Registration & Login
- JWT-based Authentication
- Role-Based Access Control (`CUSTOMER` / `ADMIN`)
- Password encryption using BCrypt

### 📦 Product Module
- Add / Update / Delete Products (Admin only)
- View all products (Public)
- View product details by ID

### 🛒 Cart Module
- Add items to cart
- Update item quantity
- Remove items from cart

### 📑 Order Module
- Place an order from cart
- View order history
- Track order status

### 💳 Payment Module
- Dummy payment flow (simulated)
- Payment status update on order

---

👨‍💻 Author
Piyush Raj
🔗 GitHub: https://github.com/thepiyushraj
🔗 LinkedIn: https://linkedin.com/in/
