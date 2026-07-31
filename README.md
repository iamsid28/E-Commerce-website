# 🛒 E-Commerce Website

A modern and responsive **E-Commerce Website** built to provide a seamless online shopping experience. The application allows users to browse products, search items, view product details, manage their shopping cart, and place orders through an intuitive user interface.

---

## 🚀 Features

* User Authentication (Login & Registration)
* Browse Products
* Product Categories
* Search Products
* Product Details Page
* Add to Cart
* Update Cart Quantity
* Remove Items from Cart
* Responsive Design
* User-Friendly Interface
* Secure Authentication
* Dynamic Product Display

---

## 🛠️ Tech Stack

### Frontend

* React.js
* HTML5
* CSS3
* JavaScript (ES6+)
* React Router
* Axios

### Backend

* Spring Boot
* Spring Security
* REST APIs
* JWT Authentication
* Spring Data JPA

### Database

* MySQL

### Tools

* IntelliJ IDEA
* VS Code
* Maven
* Git
* GitHub
* Postman

---

## 📂 Project Structure

```
E-Commerce-Website
│
├── frontend
│   ├── src
│   ├── public
│   └── package.json
│
├── backend
│   ├── controller
│   ├── service
│   ├── repository
│   ├── entity
│   ├── security
│   ├── dto
│   └── config
│
└── README.md
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/iamsid28/E-Commerce-website.git
cd E-Commerce-website
```

### Backend Setup

1. Create a MySQL database.

```sql
CREATE DATABASE ecommerce;
```

2. Configure `application.properties`

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/ecommerce
spring.datasource.username=root
spring.datasource.password=YOUR_PASSWORD

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```

3. Run the Spring Boot application.

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

---

## 📸 Screenshots

Add screenshots of the following pages:

* Home Page
* Product Listing
* Product Details
* Cart
* Login
* Register

---

## 🔐 Authentication

* User Registration
* User Login
* Password Encryption using BCrypt
* JWT Token Authentication
* Protected Routes

---

## 📌 Future Enhancements

* Wishlist
* Online Payment Integration
* Order Tracking
* Product Reviews & Ratings
* Admin Dashboard
* Inventory Management
* Email Notifications
* Discount Coupons

---

## 👨‍💻 Author

**Siddharth Bhardwaj**

GitHub: https://github.com/iamsid28

---

## ⭐ Support

If you found this project helpful, consider giving it a **⭐ Star** on GitHub.
