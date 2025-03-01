# 🍽️ Bhojan - Food Ordering App

A full-stack food ordering application built with the **MERN stack**, featuring secure payments, real-time order tracking, and a seamless user experience.

## 🚀 Features

- **User Authentication**: Secure JWT-based authentication.
- **Food Browsing & Search**: View food items by categories, tags, and search queries.
- **Cart Management**: Add/remove items from the cart with quantity selection.
- **Order Tracking**: Live tracking of orders using **Leaflet.js**.
- **Secure Payments**: Integrated **Razorpay** for hassle-free transactions.
- **Responsive UI**: Mobile-friendly design using **React.js & Tailwind CSS**.

## 🏗️ Tech Stack

- **Frontend**: React.js, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT, bcrypt
- **Payment Gateway**: Razorpay
- **Mapping & Tracking**: Leaflet.js
- **Other Tools**: Redux, Axios

## 🔧 Installation & Setup

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/rajaiswal6544/Bhojan.git
cd Bhojan
```

### 2️⃣ Backend Setup
```sh
cd backend
npm install
```
#### Set up environment variables:
Create a `.env` file in the backend directory and add:
```env
PORT=5000
MONGO_URI=your_mongo_db_uri
JWT_SECRET=your_secret_key
RAZORPAY_KEY_ID=your_key_id
RAZORPAY_KEY_SECRET=your_key_secret
```
Run the backend server:
```sh
npm start
```

### 3️⃣ Frontend Setup
```sh
cd ../frontend
npm install
```
Run the frontend server:
```sh
npm start
```



---

## 📡 API Endpoints

### 🔑 **Authentication**
| Method | Endpoint          | Description         |
|--------|------------------|---------------------|
| POST   | `/api/auth/register` | Register a new user |
| POST   | `/api/auth/login`    | Login and receive a token |

### 🛒 **Food & Orders**
| Method | Endpoint            | Description              |
|--------|--------------------|--------------------------|
| GET    | `/api/foods`       | Fetch all food items     |
| GET    | `/api/foods/:id`   | Get food item by ID      |
| POST   | `/api/orders`       | Place an order  |
| GET   | `/api/orders/:id`   | Get order details by ID      |
| POST | `/api/orders/pay`   | Process payment via Razorpay      |
---
---
## 📬 Contact
For any queries, contact **rajaiswaldev24@gmail.com** 📩

---

### 📌 Developed by Raj Jaiswal(https://github.com/rajaiswal6544)
