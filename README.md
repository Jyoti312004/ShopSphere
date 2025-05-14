# ShopSphere

A full-featured e-commerce web application built with Spring Boot that provides seamless shopping experience for customers and comprehensive management tools for administrators.

## 📋 Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Admin Panel](#admin-panel)
- [User Features](#user-features)

## ✨ Features

### User Features
- User registration and login with profile management
- Browse products by category or search by keywords
- Detailed product views with specifications
- Shopping cart management
- Order placement with COD or online payment options
- Order tracking and history
- Email notifications for order status updates

### Admin Features
- Comprehensive dashboard for business oversight
- Product management (add, edit, delete)
- Category management
- Order management with status updates
- User management
- Admin user creation

## 🛠️ Technologies Used

- **Backend**: Spring Boot, Spring Security, Spring Data JPA
- **Frontend**: Thymeleaf, Bootstrap 5, jQuery, Font Awesome
- **Database**: JPA (configured for relational database)
- **Email Service**: Java Mail Sender
- **Validation**: jQuery Validation
- **Security**: BCrypt Password Encoder

## 🗂️ Project Structure

```
shopping-cart-spring-boot/
├── src/main/
│   ├── java/com/ecom/
│   │   ├── controller/
│   │   ├── model/
│   │   ├── repository/
│   │   ├── service/
│   │   │   └── impl/
│   │   ├── util/
│   │   └── ShoppingCartApplication.java
│   └── resources/
│       ├── static/
│       │   ├── css/
│       │   ├── js/
│       │   └── img/
│       ├── templates/
│       │   ├── admin/
│       │   ├── user/
│       │   └── base.html
│       └── application.properties
```

## 🚀 Getting Started

### Prerequisites
- Java JDK 8 or higher
- Maven
- MySQL or any other supported database

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ShopSphere.git
   cd ShopSphere
   ```

2. Configure the database connection in `application.properties`

3. Build the project:
   ```bash
   mvn clean install
   ```

4. Run the application:
   ```bash
   mvn spring-boot:run
   ```

5. Access the application at `http://localhost:8080`

## 💻 Usage

### User Registration and Login
- Register a new account with your details
- Verify your email if required
- Login with your credentials

### Shopping
1. Browse products by category or use the search functionality
2. View detailed product information
3. Add products to your cart
4. Adjust quantities in the cart
5. Proceed to checkout
6. Fill in shipping information
7. Select payment method
8. Place your order

### Order Tracking
- View your order history
- Track order status (Ordered, In Progress, Packed, Out for Delivery, Delivered)
- Cancel orders if needed (before they are delivered)

## 🔧 Admin Panel

Access the admin panel by logging in with admin credentials.

### Product Management
- Add new products with details, images, pricing, and stock
- Edit existing product information
- Delete products
- Set product status (active/inactive)

### Order Management
- View all orders with filtering options
- Update order status
- View order details and customer information

### Category Management
- Add, edit, and delete product categories

### User Management
- View registered users
- Manage admin users
- Create new admin accounts

## 📱 User Features

### Cart Management
- Add products to cart
- Update quantity
- Remove items
- View total price

### Profile Management
- Update personal information
- Change password
- View order history

---

Built with ❤️ using Spring Boot
