# 🛒 UrbanBasket – Full-Stack E-commerce Platform

UrbanBasket is a full-stack e-commerce web application inspired by Blinkit, built using the *MERN stack (MongoDB, Express.js, React.js, Node.js)*. It allows users to browse products, manage carts, register/login securely, and for admins to manage product listings, categories, and more.


## 📌 Features

### 👥 User Features
- User registration and login using JWT authentication
- OTP-based email verification during signup
- Password reset functionality via email
- Browse products by category and subcategory
- Add/remove products from cart
- Checkout flow (UI level)

### 🛠 Admin Features
- Admin login with protected access
- Create, update, delete:
  - Products
  - Categories & subcategories
- Upload product images using Cloudinary
- Dashboard to manage listings

## 🧑‍💻 Tech Stack

### 🚀 Frontend
- React.js
- Tailwind CSS
- Axios
- React Router DOM

### 🔧 Backend
- Node.js
- Express.js
- MongoDB with Mongoose
- JSON Web Tokens (JWT)
- Nodemailer (for OTP & password recovery)
- Cloudinary (for image uploads)
- bcrypt (for password hashing)
- dotenv (for environment variable management)

## 📁 Folder Structure

```bash
ZippyMart/
├── client/         # Frontend (React)
├── server/         # Backend (Node + Express)
├── .env            # Environment variables
├── package.json    # Project dependencies
└── README.md       # Project documentation# UrbanBasket
