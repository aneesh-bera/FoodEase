# FoodEase — Online Food Ordering Platform

FoodEase is a full-stack food ordering web application built using the MERN stack. Users can browse food items, manage their cart, provide delivery information, place orders, make online payments, and track their order status. An admin panel is provided for managing food items and orders.

## Features

### Customer

* User registration and login
* Browse food items
* Browse food by category
* Add items to cart
* Increase or decrease item quantity
* Remove items from cart
* Checkout with delivery information
* Stripe online payment
* View placed orders
* Track order status

### Admin

* Admin login
* Add food items
* View and manage food items
* View customer orders
* Update order status
* Manage order information

## Tech Stack

* **Frontend:** React.js, React Hooks
* **Backend:** Node.js, Express.js
* **Database:** MongoDB, MongoDB Atlas
* **Authentication:** JWT, bcrypt
* **Payments:** Stripe
* **State Management:** React Context API
* **Other:** REST APIs, Multer, CORS

## Order Status

Orders can move through different stages, including:

```text
Food Processing
       ↓
Out for Delivery
       ↓
Delivered
```

## Project Structure

```text
FoodEase/
├── frontend/
├── backend/
├── admin/
└── README.md
```

## Installation

### 1. Clone the repository

```bash
git clone <your-repository-url>
cd FoodEase
```

### 2. Install dependencies

Install dependencies inside the frontend, backend, and admin directories.

```bash
npm install
```

### 3. Environment Variables

Create the required `.env` files and configure your MongoDB, JWT, Stripe, and other required credentials.

Example:

```env
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
```

Do not upload `.env` files or secret credentials to GitHub.

### 4. Run the Application

Start the backend:

```bash
npm run server
```

Start the frontend:

```bash
npm run dev
```

Run the admin panel using its configured development command.

## Authentication

JWT is used to authenticate users, while bcrypt is used to securely hash passwords.

## Payments

Stripe is integrated to handle online payments during checkout.

## Database

MongoDB is used for storing application data, with MongoDB Atlas used for database hosting.

## Author

**Aneesh Bera**

MCA Student | Full-Stack Developer | MERN Stack

