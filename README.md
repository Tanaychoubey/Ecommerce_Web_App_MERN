# MERN Stack E-Commerce Web Application

## 🌐 Live Demo
[View Live Application](https://mern-ecommerce-lyart.vercel.app/)

## 📝 Project Overview
A full-featured e-commerce web application built using the MERN (MongoDB, Express.js, React, Node.js) stack, offering a comprehensive shopping experience with robust features for both customers and administrators.

## ✨ Key Features

### 🛍️ Customer Features
- User Authentication
  - Sign Up
  - Sign In
  - Forgot Password
- Product Browsing
  - Sorting
  - Filtering
  - Pagination
- Shopping Cart Management
- Checkout Process
- Payment Integration with Stripe
- User Profile Management
- Order History Tracking

### 🔐 Authentication & Security
- JWT (JSON Web Token) Authentication
- Secure Authorization Mechanisms
- Email Notifications
  - Password Reset
  - Order Invoices

### 👑 Admin Panel
- Order Management
  - View Order History
  - Track Payment Status
- Inventory Control
  - Add/Delete Products
  - Manage Stock Levels

## 🚀 Technology Stack

### Frontend
- React.js
- Redux (State Management)
- Tailwind CSS
- React Router

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose

### Additional Technologies
- JWT for Authentication
- Stripe for Payment Processing
- Nodemailer for Email System

## 🛠️ Installation

### Prerequisites
- Node.js (v14 or later)
- MongoDB
- npm or Yarn

### Setup Instructions
1. Clone the repository
   ```bash
   git clone https://github.com/Tanaychoubey/ecommerce-mern-23.git
   ```

2. Install backend dependencies
   ```bash
   cd ecommerce-mern-23/server
   npm install
   ```

3. Install frontend dependencies
   ```bash
   cd ecommerce-mern-23/client
   npm install
   ```

4. Set up environment variables
   - Create `.env` files in both backend and frontend folders
   - Add necessary configurations (MongoDB URI, Stripe keys, JWT secret, etc.)

5. Run the application
   ```bash
   # Start backend
   cd ../server
   npm run dev

   # Start frontend (in another terminal)
   cd ../client
   npm start
   ```

## 🌈 Deployment
- Frontend deployed on Vercel
- Backend can be deployed on platforms like Heroku, AWS, or DigitalOcean

## 🤝 Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License
Distributed under the MIT License. See `LICENSE` for more information.

## 📞 Contact
Tanay Choubey - tanaychoubey2@gmail.com
---
