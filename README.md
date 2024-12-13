Sales and Invoice Management System
Welcome to the Sales and Invoice Management System project! This system is designed to automate and streamline sales tracking, product inventory management, and invoice generation. It provides a comprehensive solution for small and medium-sized businesses to manage their operations effectively.

Features
User Roles: Secure login system for admins and staff.
Product Management: Manage products with details like categories, units, taxes, and suppliers.
Customer and Supplier Management: Add, update, and track customer and supplier data.
Invoice Generation: Automatically calculate taxes and discounts, and generate printable invoices.
Sales Analytics: Visualize sales data with dynamic charts and graphs.
Responsive Design: User-friendly interface optimized for all devices.
Login Credentials
You can use the following default credentials to log in to the system:

Admin Login

Username: tahmeed@gmail.com
Password: 12345678
Prerequisites
Ensure you have the following installed:

XAMPP for PHP and MySQL.
Composer for managing PHP dependencies.
A browser to access the application.
Installation Guide
Step 1: Clone the Repository
Clone the repository using the following command:

bash
Copy code
git clone https://github.com/your-username/sales-invoice-management.git  
Or download the ZIP file from GitHub and extract it to your desired location.

Step 2: Move to XAMPP's htdocs Directory
Copy the project folder to the htdocs directory of your XAMPP installation:

makefile
Copy code
C:\xampp\htdocs\sales-invoice-management  
Step 3: Set Up the Database
Start XAMPP and ensure Apache and MySQL are running.

Open phpMyAdmin.

Create a new database:

sql
Copy code
CREATE DATABASE sales_management;  
Import the database file (sales_management.sql) located in the project folder:

Go to the Import tab in phpMyAdmin.
Select the sales_management.sql file.
Click Go to execute the import.
Step 4: Install Dependencies
Navigate to the project folder in your terminal and install required dependencies using Composer:

bash
Copy code
composer install  
Step 5: Configure the Project
Edit the config.php file in the project root to match your database credentials:

php
Copy code
$servername = "localhost";  
$username = "root";  
$password = "";  
$database = "sales_management";  

$conn = new mysqli($servername, $username, $password, $database);  
Step 6: Run the Application
Open your browser and navigate to:

arduino
Copy code
http://localhost/sales-invoice-management/  
Log in using the provided credentials to access the system.

Usage
Admin Features:
Manage product details, categories, taxes, and suppliers.
Track customer information and sales history.
Generate invoices and analyze sales through graphs.
Staff Features:
Process customer transactions.
Create and manage invoices for sales.
Update and manage product inventories.
License
This project is licensed under the MIT License. You are free to use, modify, and distribute the project as per the license terms.
