![Screenshot 2024-08-06 203201](https://github.com/user-attachments/assets/73a1b51d-d665-4b81-9806-8ed9c96af489)**Name|** SAMANJOY DAS
**Company|** CODTECH IT SOLUTIONS
**ID|** CTO8PP919
**Domain|** Python Programming
**Duration|** June to August 2024
**Mentor|** SRAVANI GOUNI


## Overview of the Project


### Project: Inventory Management System

### Objective
The Inventory Management System aims to streamline the process of managing products, tracking sales, and generating reports for low stock and sales summaries. This system provides a user-friendly interface for adding, editing, deleting, and logging sales of products, as well as viewing registered users and managing user authentication.

### Key Activities
- **User Authentication:** Login and register users with secure password handling.
- **Inventory Management:** Add, edit, and delete products in the inventory.
- **Sales Logging:** Record sales transactions and update product quantities accordingly.
- **Report Generation:** Generate reports for low stock items and sales summaries.
- **User Management:** View and manage registered users.
### Technologies Used
- **Python:** The core programming language used for the application.
- **Tkinter:** A standard GUI library in Python used for creating the user interface.
- **SQLite:** A lightweight, disk-based database used to store user, product, and sales data.
### Working of the Code
#### Database Setup
The system uses SQLite for database management. It creates three tables: users, products, and sales:

- **users:** Stores user credentials with username as the primary key.
- **products:** Stores product details such as name, quantity, and price.
- **sales:** Stores sales records, including product_id, quantity_sold, total_price, and sale_date.
### User Authentication
The authenticate function checks user credentials against the users table to allow or deny access.

### Inventory Management System
The InventorySystem class handles the main functionalities of the application:

- Tabs: The application has two main tabs - Inventory and Reports.
- **Inventory Tab:** Displays a list of products and provides buttons to add, edit, delete, and log sales of products.
- **Reports Tab:** Provides buttons to generate reports for low stock items and sales summaries.
### Product Management
- **Load Products:** Fetches and displays all products from the database.
- **Add Product:** Opens a form to add a new product to the database.
- **Edit Product:** Opens a form to edit the selected product's details.
- **Delete Product:** Deletes the selected product from the database.
### Sales Logging
The log_sale function opens a form to record a sale transaction, update the product's quantity, and insert the sale record into the database.

### Report Generation
- **Low Stock Report:** Displays products with a quantity less than 10.
- **Sales Summary Report:** Displays all sales transactions recorded in the database.
### Login Screen
The LoginScreen class handles user login, registration, and displays the list of registered users. It provides functionality to:

- **Login:** Authenticate users and open the main inventory management interface.
- **Register:** Register new users and save their credentials to the database.
- **Show Registered Users:** Display a list of registered users with an option to delete them.
