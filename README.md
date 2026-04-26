# KindKart 🛒❤️

### AI-Powered Donation Platform

KindKart is a full-stack MERN application that connects donors with children in need by enabling transparent and efficient wish fulfillment. The platform integrates AI-based recommendations, secure authentication, and online payments to create a seamless donation experience.

---

## 🚀 Features

* 🔐 User Authentication (JWT-based login/register)
* 🎁 Wish Management (Create, View, Track Wishes)
* 💳 Secure Donation System (Razorpay Integration - Test Mode)
* 🤖 AI Recommendation System (Child-based suggestions)
* 📊 Donor Dashboard (Track donations & impact)
* 🛠️ Admin Panel (Manage wishes & users)
* 🔍 Search & Filter (Category, age, urgency)
* 📦 Trust System (Wish status tracking: Requested → Funded → Delivered)

---

## 🧠 AI Module

The AI Recommendation System suggests suitable items for children based on:

* Age
* Category (Education, Health, etc.)
* Gender (optional)

Example:

* Age: 8 + Category: Education → School Bag, Books, Coloring Kit

---

## 🏗️ Tech Stack

**Frontend:** React.js
**Backend:** Node.js, Express.js
**Database:** MongoDB
**Authentication:** JWT
**Payment Gateway:** Razorpay

---

## ⚙️ Project Structure

kindkart/
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── config/
│   └── server.js
│
├── frontend/
│   ├── components/
│   ├── pages/
│   ├── services/
│   └── App.js

---

## 🔌 API Endpoints (Core)

### Auth

* POST /api/auth/register
* POST /api/auth/login

### Wishes

* GET /api/wishes
* GET /api/wishes/:id
* POST /api/wishes

### Donations

* POST /api/donations

### AI Recommendations

* POST /api/recommendations/generate

---

## 🧪 Testing

* API testing using Postman
* Authentication & validation checks
* Edge case handling (invalid inputs, unauthorized access)

---

## 🌐 Deployment

* Frontend: Vercel / Netlify
* Backend: Render / Railway
* Database: MongoDB Atlas

---

## 🔐 Environment Variables

Create a `.env` file in backend:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
RAZORPAY_KEY_ID=your_key
RAZORPAY_SECRET=your_secret

---

## 📌 Future Enhancements

* 📱 Mobile App (React Native)
* 🤖 Advanced AI (ML-based recommendations)
* 🌍 Multi-language support
* 📊 Advanced analytics dashboard
* 🔔 Real-time notifications

---

## 🎯 Project Goal

To build a transparent and scalable donation system that bridges the gap between donors and children in need using modern web technologies and AI.

---

## 👩‍💻 Author

Shambhavi Gupta
B.Tech CSE

---

## ⭐ If you like this project

Give it a star on GitHub and support the idea!
