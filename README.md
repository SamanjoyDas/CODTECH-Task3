**Name|** SAMANJOY DAS
**Company|** CODTECH IT SOLUTIONS
**ID|** CTO8PP919
**Domain|** Python Programming
**Duration|** June to August 2024
**Mentor|** SRAVANI GOUNI


## Overview of the Project
Login Page
![](https://github.com/user-attachments/assets/c6a4b30b-4837-4b6b-a3fc-2d07812e5bcf)

Login Details Filled with details and pressed Login Button
![](https://github.com/user-attachments/assets/7c0b7d58-b648-4272-92b2-d49dda938a3d)

A blank overview of the Inventory Management System
![](https://github.com/user-attachments/assets/480d61c5-e973-4041-bd8a-f2eb46b42f50)

Clicked on the Add Product Button and filled the details
![](https://github.com/user-attachments/assets/e61e89e1-f6f1-41b0-b9b5-ca4f8dae285d)

Pressed the Log Sale Button and Logged a Sale
![](https://github.com/user-attachments/assets/8b2f1b2b-0182-42ef-803f-c5364d055d95)

Popup message displayed
![](https://github.com/user-attachments/assets/c7b1b67c-0a13-4763-acda-2a435a34bfad)

Reports Tab
![](https://github.com/user-attachments/assets/8c7ff8ad-0203-4078-8802-2319ba077549)

Sales Summary Report
![](https://github.com/user-attachments/assets/c67cd7e5-a1b1-4c66-9764-128b3bb62b21)

Low Stock Report
![](https://github.com/user-attachments/assets/97f936c9-dfd2-4699-bea5-65dc17bcb396)

Register User Screen
![](https://github.com/user-attachments/assets/10a4e1b3-cb43-4b7b-9fdc-1fb3c05c811b)

Popup Screen after Registration is completed
![](https://github.com/user-attachments/assets/4bc99f93-b095-4719-b6e2-b57d21c5d569)

Registered Users list
![](https://github.com/user-attachments/assets/058a63f0-a9a8-47d9-94fd-0c4a3fe50d2c)




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
