# 🚗 Car Rental Management System (MERN Stack)

A full-stack **Car Rental Web Application** that allows users to search available cars, book them for a specific date range, and manage bookings securely.  
Built using the **MERN stack** with authentication, availability checking, and scalable backend design.

---

## 📌 Features

### 👤 User Features
- User registration & login (JWT authentication)
- Search cars by **location & date**
- Real-time car availability check
- Book cars for a selected date range
- View booking history

### 🛠 Admin Features
- Add, update, and delete cars
- Manage car availability
- View all bookings
- Control car inventory

---

## 🧑‍💻 Tech Stack

### Frontend
- **React.js**
- Context API (state management)
- Axios (API calls)
- HTML, CSS, JavaScript

### Backend
- **Node.js**
- **Express.js**
- JWT Authentication
- RESTful APIs

### Database
- **MongoDB**
- Mongoose ODM

---

## 🔐 Authentication Flow (JWT)

1. User logs in
2. Backend generates a **JWT token**
3. Token is stored in:
   ```js
   localStorage.setItem("token", data.token)
