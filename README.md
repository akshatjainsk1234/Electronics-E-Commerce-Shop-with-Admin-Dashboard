# Electronics-E-Commerce-Shop-with-Admin-Dashboard
A full-stack electronics e-commerce application where users can browse products, add to cart, place orders, and an admin can manage products, orders, and users. Built to practice authentication, API development, admin dashboards, and real-world e-commerce workflows.

Features
User Side

Browse electronics products

Product details page

Add to cart & checkout flow

User login / signup

Order history

Admin Dashboard

Add / Edit / Delete products

Manage orders

Manage users

Dashboard overview & stats

🛠️ Tech Stack

Frontend: Next.js, React, Tailwind CSS / CSS
Backend: Node.js, Express
Database: MongoDB
Auth: JWT + Cookies
State Management: Context API / Redux (agar use kiya ho)

📦 How to Run Locally
1. Clone Repo
git clone <repo-link>
cd Electronics-eCommerce-Shop-With-Admin-Dashboard-NextJS-NodeJS-main

2. Install Frontend Dependencies
cd client
npm install

3. Install Backend Dependencies
cd ../server
npm install

4. Environment Variables

Create .env in /server:

MONGO_URI=your_mongodb_url
JWT_SECRET=your_secret_key


Create .env.local in /client (if needed):

NEXT_PUBLIC_API_URL=http://localhost:5000

5. Start Backend
npm start

6. Start Frontend
npm run dev

🎯 Purpose of the Project

This project helped me learn:

Full-stack development workflow

Admin panel creation

API & database design

E-commerce architecture

Authentication & role-based access
