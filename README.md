Nandhana Traders – Interior & Exterior Printing Shop Management System

Overview

Nandhana Traders Printing Shop Management System is a desktop-based business management application developed using Python, CustomTkinter, and MongoDB. The system is designed specifically for interior and exterior printing businesses to manage inventory, purchases, sales, customer records, and business reports efficiently.

The application provides a modern graphical user interface and helps reduce manual record-keeping by maintaining all business data in a centralized database.

---

Business Domain

This software is suitable for businesses dealing with:

- Interior Printing Materials
- Exterior Printing Materials
- Flex Printing
- Vinyl Printing
- Banner Printing Materials
- Advertising Boards
- Signage Products
- Digital Printing Products
- Promotional Display Materials
- Customized Printing Orders

---

Key Features

1. User Authentication System

The application includes a secure login and registration module.

Features

- User Registration
- User Login
- Logout Functionality
- MongoDB-Based User Storage
- Duplicate Username Prevention

---

2. Inventory Management

Inventory management helps monitor available stock and product quantities.

Features

- Add Products to Inventory
- View Available Stock
- Automatic Stock Updates
- Real-Time Quantity Tracking
- Product ID Management

Stored Information

- Product ID
- Product Name
- Product Quantity

---

3. Purchase Management

The purchase module records incoming products and updates stock automatically.

Features

- Add New Purchases
- Calculate Total Purchase Amount
- Automatic Stock Increase
- Purchase Record Storage

Purchase Details

- Product Name
- Product ID
- Product Price
- Product Quantity
- Total Amount

---

4. Sales Management

The sales module manages customer purchases and inventory deduction.

Features

- Add Sales Transactions
- Automatic Amount Calculation
- Stock Availability Verification
- Automatic Stock Reduction
- Sales History Storage

Sales Details

- Product Name
- Product ID
- Product Price
- Quantity Sold
- Total Amount

---

5. Customer Management

Customer information can be stored and managed for future reference.

Features

- Customer Registration
- Customer Purchase Tracking
- Contact Information Storage
- Order History Maintenance

Customer Details

- Customer Name
- Contact Number
- Product Purchased
- Quantity
- Price
- Total Amount

---

6. Business Reports

The system generates Excel reports for business analysis and record keeping.

Available Reports

Stock Report

- Product Inventory Details
- Current Quantity Status

Purchase Report

- Complete Purchase Records
- Purchase Amount Analysis

Sales Report

- Product Sales Records
- Revenue Tracking

Customer Report

- Customer Purchase Information
- Customer Contact Details

---

Technology Stack

Technology| Purpose
Python| Core Programming Language
CustomTkinter| Modern GUI Development
Tkinter| User Interface Components
MongoDB| Database Management
PyMongo| MongoDB Connectivity
OpenPyXL| Excel Report Generation
Pillow (PIL)| Image Processing
UUID| Unique Record Identification
Matplotlib| Future Data Visualization

---

Database Structure

Database Name

maniraj

Collections

user

Stores authentication information.

{
  "username": "admin",
  "password": "password123",
  "email": "admin@gmail.com"
}

---

stock

{
  "product_id": "P101",
  "product_name": "Flex Banner",
  "product_quantity": 100
}

---

purchase

{
  "product_name": "Flex Banner",
  "product_id": "P101",
  "product_price": 150,
  "product_quantity": 50,
  "product_amount": 7500
}

---

sales

{
  "NAME": "Flex Banner",
  "ID": "P101",
  "PRICE": 200,
  "QTY": 10,
  "AMT": 2000
}

---

customer

{
  "product_name": "Flex Banner",
  "product_id": "P101",
  "customer_name": "John",
  "product_price": 200,
  "product_quantity": 5,
  "product_amount": 1000,
  "customer_contact": "9876543210"
}

---

Application Workflow

Step 1

User logs in to the system.

Step 2

Products are added through the Purchase Module.

Step 3

Purchased products are automatically added to inventory.

Step 4

Sales transactions are recorded.

Step 5

Stock quantity is automatically updated after sales.

Step 6

Customer details are stored.

Step 7

Excel reports are generated whenever required.

---

Installation Guide

Clone Repository

git clone https://github.com/your-username/nandhana-traders-printing-management-system.git

Move Into Project Folder

cd nandhana-traders-printing-management-system

Install Required Packages

pip install customtkinter
pip install pymongo
pip install pillow
pip install openpyxl
pip install matplotlib

Or use:

pip install -r requirements.txt

---

MongoDB Setup

Install MongoDB Community Edition.

Start MongoDB service.

Default connection used:

client = MongoClient(port=27017)

Ensure MongoDB is running on:

localhost:27017

---

Run the Application

python main.py

---

Folder Structure

nandhana-traders-printing-management-system/
│
├── main.py
├── README.md
├── requirements.txt
│
├── assets/
│   ├── logo.png
│   ├── login.png
│   └── banner.png
│
├── screenshots/
│   ├── login-page.png
│   ├── register-page.png
│   ├── stock-page.png
│   ├── purchase-page.png
│   ├── sales-page.png
│   └── customer-page.png
│
└── reports/

---

Future Enhancements

- Sales Dashboard
- Revenue Analytics
- Monthly Profit Reports
- Supplier Management
- Invoice Generation
- PDF Export
- Barcode Scanning
- QR Code Integration
- Product Search System
- Multi-User Access Control
- Cloud Database Support

---

Benefits

- Easy Inventory Tracking
- Reduced Manual Work
- Accurate Stock Management
- Faster Sales Processing
- Customer Record Maintenance
- Automated Excel Reporting
- Improved Business Efficiency

---

Developed For

Nandhana Traders

Interior & Exterior Printing Materials, Advertising Products, Sign Boards, Flex Printing, Vinyl Printing, and Related Printing Solutions.

---

License

This project is developed for educational and business management purposes.

© Nandhana Traders. All Rights Reserved.
