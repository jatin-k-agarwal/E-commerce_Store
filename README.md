# Install Dependencies

**For Backend** - `npm i`

**For Frontend** - `cd frontend` ` npm i`
🛒 E-commerce Store — MERN Stack Full-Stack Project
A full-featured E-Commerce Web Application built using the MERN Stack (MongoDB, Express.js, React.js, Node.js). This project includes User Authentication, Admin Dashboard, Product Management, Cart, Orders, Payment Integration, Reviews & Ratings, and a lot more.

🌐 Live Demo
Frontend: https://your-frontend.vercel.app
Backend API: https://your-backend.onrender.com/api/v1
(Update these links after deployment)

📂 Project Structure
bash
Copy code
E-commerce_Store/
 ├── backend/       # Node.js + Express + MongoDB (API & Admin)
 ├── frontend/      # React.js + Redux Toolkit (Client App)
 ├── uploads/       # (Optional) Local image storage
 ├── README.md
 └── .gitignore
🚀 Features
User Registration, Login & Profile Management

JWT Authentication & Authorization (Protected Routes)

Product Catalog with Search & Filtering

Product Ratings & Reviews

Shopping Cart & Checkout Process

Payment Gateway Integration (Stripe/Razorpay)

Order Tracking & History

Admin Dashboard for Product, Order, and User Management

Product Image Uploads (Local / Cloudinary)

Fully Responsive UI (Mobile-First Design)

Secure APIs with Role-Based Access Control (RBAC)

🛠️ Tech Stack
Frontend	Backend	Database
React.js, Redux Toolkit	Node.js, Express.js	MongoDB
Axios, React-Router-DOM	JWT Authentication	Mongoose
TailwindCSS / Bootstrap	Stripe/Razorpay Payment Gateway	

⚙️ Getting Started (Run Locally)
1. Clone the Repository
bash
Copy code
git clone https://github.com/jatin-k-agarwal/E-commerce_Store.git
cd E-commerce_Store
2. Backend Setup
bash
Copy code
cd backend
npm install
# Create backend/config/config.env and add necessary variables
npm start
3. Frontend Setup
bash
Copy code
cd ../frontend
npm install
npm start
📝 Environment Variables
Backend (/backend/config/config.env)
env
Copy code
PORT=5000
DB_URI=your_mongoDB_connection_string
JWT_SECRET=your_jwt_secret_key
STRIPE_API_KEY=your_stripe_api_key
CLOUDINARY_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
Frontend (/frontend/.env)
env
Copy code
REACT_APP_API_URL=https://your-backend-url/api/v1
🚀 Deployment Guide
Frontend Deployment (Vercel)
Go to Vercel

Import your GitHub Repository

Select /frontend as the Root Directory during setup

Add Environment Variable:

env
Copy code
REACT_APP_API_URL=https://your-backend-url/api/v1
Deploy 🚀

Backend Deployment (Render)
Go to Render

New → Web Service → Connect your GitHub Repo

Select /backend as the Root Directory

Set Build Command: npm install

Start Command: npm start

Add Environment Variables from /backend/config/config.env

Deploy 🚀

📚 Resources
React Documentation

Redux Toolkit

Express.js Documentation

MongoDB & Mongoose

Stripe Developer Docs

Render Deployment Guide

🙌 Contributing
Contributions, issues, and feature requests are welcome!

bash
Copy code
git clone https://github.com/jatin-k-agarwal/E-commerce_Store.git
