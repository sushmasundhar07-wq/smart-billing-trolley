# Smart Billing Trolley – Software Simulation

## Project Overview

The ""Smart Billing Trolley"" is a software simulation project designed to simplify the shopping and billing process in supermarkets. It provides a user-friendly website where customers can view products, add items to their shopping cart, and calculate the total bill digitally.

The main objective of this project is to demonstrate how a smart trolley billing system can reduce manual billing work, save time, and improve the shopping experience.

This project is implemented as a web-based software simulation using PHP, MySQL, HTML, CSS, and JavaScript.

## Objectives

- To simplify the product selection and billing process.
- To calculate the total cost of selected products automatically.
- To maintain product information in a database.
- To reduce manual calculation errors.
- To demonstrate the working of a smart billing system through a website.
- To provide a simple and user-friendly shopping interface.

## Technologies Used

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** PHP
- **Database:** MySQL
- **Local Server:** Apache using XAMPP
- **Development Environment:** Visual Studio Code
- **Database Management:** phpMyAdmin

## Features

- User-friendly website interface.
- Product listing using database records.
- Shopping cart and product selection functionality, where implemented.
- Automatic bill calculation, where implemented.
- Database integration using MySQL.
- Local website execution through XAMPP.
- Software-based simulation of a smart trolley billing process.

## How the System Works

1. The user opens the Smart Billing Trolley website.
2. The website displays the available products.
3. The user selects products for shopping.
4. The system calculates the bill based on the selected products and their prices.
5. The user can review the selected items and total amount, depending on the implemented features.

The project simulates the billing process through software rather than requiring a physical smart trolley or hardware components.

## System Requirements

- Windows operating system
- XAMPP Server
- Visual Studio Code
- Web browser such as Google Chrome
- PHP and MySQL, provided through XAMPP

## Installation and Setup

### Step 1: Clone the Repository

Open a terminal and run:

```bash
git clone https://github.com/sushmasundhar07-wq/smart-billing-trolley.git
```

### Step 2: Move the Project Folder

Copy or move the project folder into the XAMPP `htdocs` directory:

```text
C:\xampp\htdocs\smart-billing-trolley
```

### Step 3: Start XAMPP

1. Open the XAMPP Control Panel.
2. Start **Apache**.
3. Start **MySQL**.

### Step 4: Import the Database

1. Open `http://localhost/phpmyadmin/` in your browser.
2. Create a database named `smart_billing_trolley`, if it does not already exist.
3. Select the database.
4. Import the SQL files provided with the project, if required.

### Step 5: Configure the Database

Check the project's PHP database connection file and ensure that the database name, username, password, and host match your local MySQL configuration.

Typical local settings are:

- Host: `localhost`
- Username: `root`
- Password: Empty by default in many XAMPP installations
- Database: `smart_billing_trolley`

Use the actual credentials configured on your computer.

### Step 6: Run the Website

Open the following URL in your browser:

```text
http://localhost/smart-billing-trolley/
```

The Smart Billing Trolley website should now open locally.

## Project Type

**Software Simulation – Web-Based Application**

This project demonstrates the concept of smart shopping and digital billing using web technologies and a database. It does not require physical trolley hardware to demonstrate the software workflow.

## Future Enhancements

- Barcode scanning integration.
- QR code-based product identification.
- Online payment integration.
- Customer login and shopping history.
- Product image support.
- Inventory and stock management.
- Receipt generation and printing.
- Integration with a physical smart trolley.

## Applications

- Supermarkets
- Retail stores
- Shopping malls
- Grocery stores
- Academic software simulation projects

## Conclusion

The Smart Billing Trolley software simulation demonstrates how web technologies can be used to improve the shopping and billing experience. By combining PHP, MySQL, and a user-friendly interface, the project provides a foundation for a more efficient and automated retail billing system.

## Author

Developed as an academic software simulation project.
