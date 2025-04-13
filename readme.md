# 🛒 ProShop – MERN Stack eCommerce Platform

🚀 Live Demo: https://shoppro-xcra.onrender.com/

ProShop is a **full-featured eCommerce platform** that I designed, built, and deployed using the **MERN stack** (MongoDB, Express, React, Node.js). It’s developed with a strong focus on performance, scalability, and user experience — from authentication and product management to payments and admin control.

This project simulates a real-world eCommerce environment with dynamic frontend functionality, secure backend architecture, and third-party integration like **PayPal**.

---

## 🔧 Features

The app is called **ProShop**, and it's a complete online store with all the essential eCommerce features:

- 🛍️ Shopping cart with real-time quantity control
- 📝 Product reviews and star ratings
- 🔍 Search functionality, top product carousel, and pagination
- 🔐 Secure JWT authentication with HTTP-only cookies
- 👤 User profile with update support and order history
- 🛠️ Admin panel for managing users, products, and orders
- 💳 PayPal & card payment integration
- ✅ Order delivery status tracking
- 📦 Custom database seeder script for quick setup

---

## 🚀 Tech Stack

### **Frontend:**

- React (with hooks and functional components)
- Redux Toolkit for state management
- React Router for routing
- React-Bootstrap for UI components

### **Backend:**

- Node.js with Express.js
- MongoDB with Mongoose ODM
- JWT for authentication
- Cookie-parser for secure cookie handling

### **Other Tools & Services:**

- PayPal REST API integration
- Multer for image upload handling
- dotenv for environment configuration
- Concurrently for dev workflow
- Deployment via Vercel

---

## 🧠 What I Built

- A full-scale MERN stack application from scratch
- A RESTful API with Express.js and MongoDB
- Full authentication system using JWT and cookies
- Admin dashboard to manage the entire store
- Complex Redux state management with slices, async thunks, and middleware
- Cart and order systems tied to user accounts
- Custom pagination, search, and carousel logic
- Payment processing via PayPal
- Protected routes with role-based access
- Frontend UI/UX built with React-Bootstrap
- A complete deployment-ready architecture

---

## 📸 Screenshots

### 🖥️ Home Page

![Home Page](frontend/images/Screenshot%202025-04-13%20at%2016.06.54.png)

---

## 🏁 Getting Started

### ⚙️ Installation

```bash
# 1. Clone the repository
git clone https://github.com/your-username/proshop.git
cd proshop

# 2. Install backend dependencies
cd backend
npm install

# 3. Install frontend dependencies
cd frontend
npm install
```

### 🌐 Environment Variables

```bash
NODE_ENV=development
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PAYPAL_CLIENT_ID=your_paypal_client_id

```

### ▶️ Running the App

```bash
# Backend
cd backend
npm run server

# Frontend
cd frontend
npm start


```
