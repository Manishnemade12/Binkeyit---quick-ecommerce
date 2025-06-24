# 🛍️ Binkeyit — Quick E-commerce Platform

**Binkeyit** is a fully-featured e-commerce application built with the **MERN stack** (MongoDB, Express.js, React, Node.js). It includes complete **user** and **admin dashboards**, robust authentication, payment processing, and advanced store management functionalities — all packed in one modern web app.

---

## ✨ Features

### 🔐 Authentication & Security
- JWT-based authentication with **Access** & **Refresh Tokens**
- **Secure login** & signup flows
- Password encryption & validation
- Route protection for both admin & user sides

### 🧑‍💼 User Side
- Register and login functionality
- Browse products by category
- Add to cart & manage cart
- Apply **coupon codes** for discounts
- Checkout securely using **Stripe**
- View order history and profile details

### 👑 Admin Dashboard
- Admin login with protected routes
- **Product management** (CRUD)
- **Category management**
- Manage orders and track sales
- Apply and manage **discount codes**
- View **sales analytics** via dynamic charts

### 💳 Payment Integration
- Stripe API setup for secure payment gateway
- Full cart-to-checkout process
- Order confirmation on successful payment

### 📦 Backend Tech
- **MongoDB** database
- **Node.js** and **Express.js** server
- RESTful APIs
- **Resend** integration (for email notifications like order confirmations)

### 🎨 Frontend Tech
- **React.js** with Tailwind CSS
- Fully responsive design
- Seamless UI/UX for both user and admin panels

---

## ⚙️ Tech Stack

- **Frontend**: React, Tailwind CSS, Axios
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (Access + Refresh Tokens)
- **Payments**: Stripe
- **Email**: Resend
- **State Management**: React Context / Redux (based on your setup)

---

## 🚀 Getting Started

### 🔧 Prerequisites
- Node.js
- MongoDB (local or cloud)
- Stripe account
- Resend API key

### 🛠️ Setup

```bash
# Clone the repository
git clone https://github.com/Manishnemade12/Binkeyit---quick-ecommerce.git
cd binkeyit-ecommerce

# Install backend dependencies
cd server
npm install

# Install frontend dependencies
cd ../client
npm install

# Create environment files
# In both /client and /server directories, set up:
# .env

# Start backend
cd ../server
npm run dev

# Start frontend
cd ../client
npm start
