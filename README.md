🛍️ MERN E-Commerce Web Application

A full-stack E-Commerce platform built using the MERN Stack (MongoDB, Express.js, React.js, Node.js) that allows users to browse products, filter collections, add items to cart, place orders, and complete secure payments.

This project includes a complete user storefront and a separate admin dashboard to manage products and orders.

The goal of this project was to understand how a real e-commerce system works from frontend to backend, including product management, authentication, payments, image handling, and order processing.

While building this project I explored multiple approaches, experimented with my own ideas, and also learned a lot from GreatStack tutorials, which helped me understand the architecture and implementation of a real MERN project.

🚀 Project Highlights

• Full MERN Stack E-Commerce Application
• User Storefront with modern UI
• Complete Admin Dashboard
• Secure Authentication System
• Stripe Online Payment Integration
• Cash On Delivery Support
• Cloudinary Image Upload System
• MongoDB Database Storage
• Product Filtering and Search
• Dynamic Cart System
• Order Tracking System

🛠 Tech Stack
Frontend
• React.js
• Vite
• Tailwind CSS
• Context API for state management

Backend
• Node.js
• Express.js
• REST API architecture

Database
• MongoDB
https://www.mongodb.com/

Stores all application data including:
• Users
• Products
• Orders

Image Storage
• Cloudinary
https://cloudinary.com/
Used to upload product images and convert them into image URLs stored in MongoDB.

Payment Gateway
• Stripe
https://stripe.com/
Used to handle secure online payments.

# 📂 Project Architecture

```
E-commerceWebApp
│
├── backend
│   ├── config
│   ├── controllers
│   ├── middleware
│   ├── models
│   ├── routes
│   └── server.js
│
├── admin
│   ├── public
│   └── src
│       ├── components
│       ├── pages
│       └── assets
│
├── frontend
│   ├── public
│   └── src
│       ├── components
│       ├── pages
│       ├── context
│       └── assets
│
└── README.md
```

🧑‍💻 Frontend Features

The frontend represents the customer-facing side of the e-commerce platform.

Users can:

Browse products

View product details

Add items to cart

Place orders

Track their purchases

🏠 Home Page

The homepage displays:

🆕 Latest product collections

⭐ Best seller products

🎯 Promotional banner section

🛍 Featured product grid

This page helps users quickly discover trending products.

🛍 Collection Page

The collection page shows the complete list of available products.

Features include:

📂 Category filtering

🧩 Subcategory filtering

🔎 Product search functionality

💰 Price filtering

These filters help users quickly find specific products.

📄 Product Detail Page

Each product has a dedicated page displaying:

🖼 Product image gallery

📝 Product description

💲 Price information

📏 Size selection options

🛒 Add to cart functionality

🔗 Related product suggestions

🛒 Cart System

The cart system allows users to:

➕ Add products to cart

🔢 Update product quantity

❌ Remove products

💰 View cart totals

🚚 Calculate shipping charges

The cart icon in the navbar dynamically updates based on the number of items.

💳 Checkout Page

Before placing an order, users must provide delivery details including:

👤 First Name

👤 Last Name

📧 Email

🏠 Address

🌆 City

🛣 Street

📮 Zip Code

📱 Phone Number

💰 Payment Options

Two payment methods are available.

💳 Stripe Online Payment

Users can securely pay using the Stripe Payment Gateway.

Stripe handles:

Card validation

Payment processing

Secure transactions

🔗 https://stripe.com/

💵 Cash On Delivery (COD)

Users can also place orders without online payment.

📦 Orders Page

Users can track their orders with details such as:

📦 Ordered products

💳 Payment method

📅 Order date

🚚 Delivery status

Order statuses include:

🟢 Order Placed

📦 Packing

🚚 Shipping

✅ Delivered

🔐 Authentication System

The platform includes a secure user authentication system.

Users can:

📝 Create new accounts (Signup)

🔑 Log into existing accounts

📦 Access their personal order history

All user information is securely stored in MongoDB.

🛠 Admin Panel Features

The project includes a separate Admin Dashboard used to manage the store.

🔐 Admin Login

Admins must log in to access the dashboard.

This ensures secure product and order management.

➕ Add Product

Admins can add new products by entering:

🖼 Product images

📝 Product name

📄 Product description

📂 Product category

🧩 Product subcategory

💲 Product price

📏 Available sizes

⭐ Bestseller option

Product images are uploaded to Cloudinary and stored as URLs.

📋 Product List Management

Admins can view all products in a structured table showing:

🖼 Product image

🏷 Product name

📂 Product category

💲 Product price

Admins can also remove products from the database.

📦 Order Management

Admins can monitor and manage all customer orders.

The admin panel displays:

👤 Customer details

🏠 Delivery address

📦 Ordered items

💳 Payment method (Stripe or COD)

💰 Order total

✔ Payment status

Admins can update order status such as:

🟢 Order Placed

🚚 Delivered

⚙ Backend Features

The backend handles the business logic and API communication.

Main responsibilities include:

🔐 User authentication

🛍 Product management

📦 Order creation

💳 Payment verification

☁ Image uploading

🗄 Database operations

🗄 Database Collections

MongoDB stores three main collections.

👤 Users

Stores registered user information.

🛍 Products

Stores all products added through the admin panel.

📦 Orders

Stores complete order information including:

👤 Customer details

🛍 Ordered items

💳 Payment method

📦 Order status
```
🔄 Application Workflow
User Browses Products
        ↓
Add To Cart
        ↓
Cart Page
        ↓
Checkout Page
        ↓
Select Payment Method
        ↓
Stripe Payment / COD
        ↓
Order Created
        ↓
Admin Processes Order
```

📸 Application Screenshots


```
# 📸 Application Screenshots

## 🏠 Home Page
![Home](./Screenshot/Frontend%20UI/home%20page.png)

## 🛍 Collection Page
![Collection](./Screenshot/Frontend%20UI/collection%20page.png)

## 📄 Product Detail Page
![Product](./Screenshot/Frontend%20UI/Detailed%20page.png)

## 🛒 Cart Page
![Cart](./Screenshot/Frontend%20UI/Cart%20page.png)

## 💳 Checkout Page
![Checkout](./Screenshot/Frontend%20UI/payment%20page.png)

## 📦 Orders Page
![Orders](./Screenshot/Frontend%20UI/Orders%20page.png)

## 🔐 Login Page
![Login](./Screenshot/Frontend%20UI/Login%20Page.png)

## 📝 Signup Page
![Signup](./Screenshot/Frontend%20UI/Signup%20page.png)

## ℹ️ About Page
![About](./Screenshot/Frontend%20UI/about%20page.png)

## 📞 Contact Page
![Contact](./Screenshot/Frontend%20UI/Contact%20page.png)

---

# 🛠 Admin Panel Screenshots

## 🔐 Admin Login
![Admin Login](./Screenshot/Admin%20Panel%20UI/login%20admin.png)

## ➕ Add Product
![Add Product](./Screenshot/Admin%20Panel%20UI/products%20adding%20features.png)

## 📋 Product List
![Product List](./Screenshot/Admin%20Panel%20UI/list%20of%20data%20that%20added.png)

## 📦 Orders Management
![Orders Management](./Screenshot/Admin%20Panel%20UI/Order%20page.png)

```
# ⚙ Installation & Setup

```markdown
# 📋 Prerequisites

Make sure you have installed:

- Node.js
- npm
- MongoDB account
- Cloudinary account
- Stripe account
```

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/ecommerce-mern.git
cd ecommerce-mern

2️⃣ Install Backend Dependencies
cd backend
npm install

3️⃣ Install Frontend Dependencies
cd frontend
npm install

4️⃣ Install Admin Panel Dependencies
cd admin
npm install

5️⃣ Run Backend Server
cd backend
npm run server

6️⃣ Run Frontend Application
cd frontend
npm run dev

7️⃣ Run Admin Panel
cd admin
npm run dev
```

🙏 Acknowledgement

While building this project, I explored different resources and tutorials to understand the MERN stack ecosystem.

I also learned many important concepts and implementation approaches from GreatStack tutorials, which helped me better understand how to structure and build a full-stack e-commerce application.

Along with that guidance, I experimented with my own ideas, made changes, and implemented features to deepen my understanding of full-stack development.
