# E-Commerce Shopping Management System

**Project Description**
This project is an E-Commerce Shopping Management System developed in C++. It provides a comprehensive solution for user registration, product management, shopping cart functionality, and payment processing. The system allows administrators to manage products and users, while customers can register, log in, browse products, add products to their shopping cart, and make payments.

**Features**

**User Registration and Login**
+ Users can register with their full name, gender, phone number, email, address, username, and password.
+ Registered users can log in using their username and password.
+ User details are stored in a binary file for secure access.

**Product Management**
+ Administrators can add and remove products from the product list.
+ Each product has an ID, name, and price.
+ Product details can be displayed in a formatted list.

**Shopping Cart**
+ Customers can add products to their shopping cart by entering the product ID.
+ Customers can view the products in their cart, along with the total price and quantity.
+ Customers can remove products from their cart.

**Payment Processing**
+ The system supports payment via credit/debit cards and online banking.
+ Payment details such as card number, PIN, and online banking credentials are securely processed.
+ Successful payments are acknowledged with a confirmation message.

## Classes and Methods

**Register Class**
+ Manages user registration and login.
+ Stores user details and credentials in a binary file.
+ Handles input validation and exception handling for secure login.

**Product Class**
+ Represents individual products with ID, name, and price.
+ Methods to set and get product details.

**ProductList Class**
+ Manages a list of products.
+ Methods to display, add, and remove products from the list.

**Administrator Class**
+ Inherits from Register and ProductList classes.
+ Manages administrator-specific tasks such as adding and removing products.
+ Validates administrator credentials for secure access.

**ShoppingCart Class**
+ Manages the shopping cart for customers.
+ Methods to add, remove, and display selected products.
+ Calculates the total price and quantity of products in the cart.

**Payment Class**
+ Handles payment processing for purchases.
+ Supports multiple payment methods with secure input handling.
+ Displays payment confirmation and receipt details.

**Customer Class**
+ Inherits from Register and ShoppingCart classes.
+ Manages customer-specific tasks such as viewing profiles and ordering products.
+ Generates and prints customer invoices.
