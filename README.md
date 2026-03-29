# 🚀 E-Commerce App (.NET 8 + Angular)

A full-stack **E-Commerce web application** built using **ASP.NET Core (.NET 8)** for the backend and **Angular** for the frontend.  
The system provides a complete online shopping experience, including authentication, product management, orders, payments, and ratings.

---

## 🧩 Architecture

The backend follows **Clean Architecture** principles and is structured into:

- **Ecom.API** → Handles HTTP requests (Controllers & Middleware)  
- **Ecom.Core** → Domain entities, DTOs, and business logic interfaces  
- **Ecom.Infrastructure** → Data access, repositories, and service implementations  

Frontend is built separately using **Angular**.

---

## ✨ Features

### 👤 Authentication & Users
- User registration & login with JWT authentication  
- Secure token generation  

### 🛍️ Products & Categories
- Product listing with filtering & pagination  
- Category management  
- Product ratings system  

### 🛒 Basket & Orders
- Shopping cart (basket) management  
- Create and manage orders  
- Order tracking  

### 💳 Payments
- Payment integration and processing  
- Order-payment workflow handling  

### ⭐ Additional Features
- Image upload & management  
- Email service integration  
- Global exception handling middleware  
- Clean API response handling  

---

## 🛠️ Tech Stack

### 🔹 Backend
- ASP.NET Core (.NET 8)  
- Entity Framework Core  
- SQL Server  
- Repository & Unit of Work Pattern  
- JWT Authentication  

### 🔹 Frontend
- Angular  
- TypeScript  
- HTML / CSS  

### 🔹 Tools & Practices
- Clean Architecture  
- RESTful APIs  
- Middleware (Exception Handling)  
- Auto Mapping (Custom Mapping Classes)  

---

## 📂 Project Structure
