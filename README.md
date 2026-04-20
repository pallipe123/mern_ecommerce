# 🛒 MERN E-Commerce Platform

A full-stack e-commerce web application built using the MERN stack (MongoDB, Express, React, Node.js). This platform allows users to browse products, manage cart, and simulate online shopping with a modern UI.

---

## 🌐 Live Demo

👉 https://mern-ecommerce-pi-steel.vercel.app/

Explore the app:

* Browse products
* Add items to cart
* View cart and manage items

---

## 🚀 Features

### 👤 User Authentication

* User Registration (Signup)
* User Login
* Secure authentication system

### 🛍️ User Features

* View all available products
* Product listing with images, price, and details
* Add to cart functionality
* Remove items from cart
* Cart summary with total price

### 📦 Product Management

* Dynamic product display from backend
* Clean UI for product cards

### 🧠 Core Functionality

* State management for cart
* API integration between frontend and backend
* Responsive design

---

## 🛠️ Tech Stack

### Frontend:

* React (Vite)

### Backend:

* Node.js
* Express.js

### Database:

* MongoDB Atlas (Cloud Database)

---

## 📂 Project Structure

```id="x1f7r2"
mern-ecommerce/
│
├── backend/
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   └── server.js
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── App.jsx
│
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```id="r6p8k1"
git clone https://github.com/your-username/mern-ecommerce.git
cd mern-ecommerce
```

---

### 2️⃣ Backend Setup

```id="y3n4t8"
cd backend
npm install
```

Create `.env` file:

```id="q9m2s7"
MONGO_URI=your_mongodb_connection_string
PORT=5000
```

Run backend:

```id="k5d1a9"
node server.js
```

---

### 3️⃣ Frontend Setup

```id="t2v8c4"
cd frontend
npm install
npm run dev
```

---

## ⚠️ Note

* Payment functionality is not yet integrated
* This project simulates shopping flow
* Backend must be deployed for full functionality

---

## 💡 Future Improvements

* Payment integration (Razorpay/Stripe)
* Order management system
* Admin dashboard
* Product search & filtering

---

## 🤝 Contribution

Feel free to fork and improve this project.

---

## 📜 License

This project is for educational purposes.

---

## 🌟 Tagline

**"Simple and secure shopping experience powered by MERN stack"**
