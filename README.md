# E-Commerce Product Catalog

This is a full-stack web application for managing an online product catalog. It uses **MongoDB**, **Express.js**, **React**, and **Node.js (MERN stack)**.

## 📌 Features

- Add new products (name, description, price, category)
- View all products
- Connected to a MongoDB database
- Ready for future additions like categories, reviews, authentication

## 🏗️ Project Structure

ECommerceProductCatalog/
├── backend/ # Node.js + Express API with MongoDB
└── frontend/ # React Frontend

## 🚀 Installation & Running

### 1️⃣ Backend Setup

```bash
cd backend
npm install
cp .env.example .env  # Add your MongoDB URI to .env
npm run dev
cd frontend
npm install
npm start

🌐 API URL: http://localhost:5000/api/products
