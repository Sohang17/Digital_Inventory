# CPC - Inventory Management System

CPC (Central Police Canteen) is an Inventory Management System built using PHP and a MySQL database. It allows users to manage products, track inventory, and perform various operations in an easy and efficient manner. This README provides an overview of the project's features and instructions for setting up and using the system.

## Features

- Admin Panel:
  - Secure login with hashed passwords
  - Add, modify, and remove products
  - Update product quantities and prices
  - View and manage orders
  - Generate sales reports

- User Interface:
  - Browse products by category
  - Add products to the cart
  - View and modify the cart
  - Generate and view order history
  - Generate and view invoices

## Technologies Used

- PHP for server-side scripting
- SQL for database management
- HTML/CSS for frontend design
- JavaScript for interactive features

## Prerequisites
Install Git on your system.
Download and install EasyPHP DevServer for a local PHP development environment.

## Getting Started

Follow these steps to set up and run the CPC Inventory Management System on your local machine.

**1.Clone the Repository:**

Open a terminal/command prompt and navigate to a directory where you want to clone the project.

git clone https://github.com/your-username/cpc.git
cd cpc

**2.Database Setup:**

Open EasyPHP DevServer .
Access PhpMyAdmin by clicking on "MySQL Administration" for the MySQL component.
Create a new database named inventory.
Import the database schema from the inventory.sql file in PhpMyAdmin.

**3.Project Placement:**

Open the "Portable Directory" of EasyPHP DevServer.
Copy the cloned project folder (cpc) into this directory.

**4.Start Servers:**

Start the HTTP server and the database server using EasyPHP DevServer.

**5.(1)Access User Interface:**

Open your web browser.
Navigate to http://127.0.0.1:8080/cpc/user/loginindex.html to access the user interface.

**5.(2)Access Admin Interface:**

Navigate to http://127.0.0.1:8080/cpc/admin/loginindex.html to access the admin interface.

## Usage

Admin Interface: Access the admin panel using the provided credentials. Manage products, orders, and generate reports.

User Interface: Browse products, add them to the cart, view the cart, and place orders.

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.

## Contact

For any inquiries or questions, feel free to contact us at patelsohang123@gmail.com.
