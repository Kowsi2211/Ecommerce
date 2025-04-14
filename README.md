# Ecommerce
eCommerce Website with User & Guest Checkout Integration

This project is a fully functional eCommerce website built with Django, featuring both authenticated user and guest checkout capabilities. The site supports physical and digital products, with a streamlined checkout process. Key features include:

User Authentication: Customers can register and log in to view their order history and track pending orders.

Guest Checkout: Customers can purchase items without creating an account, with order details stored in cookies. They have the option to create an account after completing their purchase.

Payment Integration: PayPal payment gateway for both PayPal accounts and debit/credit card transactions. Stripe integration is planned for future expansion.

Data Models:

User: Built-in Django user model for customer registration.

Customer: One-to-one relationship with User model for customer-specific details.

Product: Represents the products available for purchase.

Order: Tracks customer orders, status, and transaction details.

OrderItem: Represents individual items within an order.

Shipping: Contains shipping details for physical product orders.

The goal of this project is to provide a seamless shopping experience for both authenticated users and guests, with a simple and secure checkout process.
![er diagram](https://github.com/user-attachments/assets/a8cc5664-8bb8-4262-9e74-04393ba99cbf)

