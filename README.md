# Electricity-Bill-Management-System
A web-based Electricity Bill Management System developed using HTML, CSS, PHP, MySQL, and XAMPP for managing electricity consumers, meter readings, bill generation, and payment records.
# ⚡ Electricity Bill Management System

## 📌 Project Overview

The Electricity Bill Management System is a web-based application designed to automate electricity billing and consumer management. The system enables consumers to register, view their electricity usage, check generated bills, and manage payment records. It also provides an administrator panel to manage consumers, meter readings, bill generation, and payment details efficiently.

This application reduces manual billing errors, improves record management, and provides a secure and user-friendly platform for electricity bill administration.

This project was developed as a **BCA Final Year Project**.

---

## 🎯 Objectives

* To automate electricity bill generation.
* To maintain consumer and billing records digitally.
* To reduce manual calculation errors.
* To simplify bill payment and record management.
* To improve efficiency in electricity billing operations.

---

## 🛠️ Technologies Used

### Frontend

* HTML5
* CSS3
* JavaScript
* Bootstrap

### Backend

* PHP

### Database

* MySQL

### Server

* XAMPP (Apache & MySQL)

### Tools

* Visual Studio Code
* MySQL Workbench
* Git & GitHub

---

## ✨ Features

### 👤 Consumer Module

* Consumer Registration
* Secure Login & Logout
* View Consumer Profile
* View Electricity Bills
* View Meter Reading History
* Download Bill
* View Payment History
* Update Profile

---

### 🔐 Admin Module

* Admin Login
* Dashboard
* Manage Consumers
* Add / Update Meter Readings
* Generate Electricity Bills
* Manage Payments
* View Billing Reports
* Search Consumer Records
* Monthly Bill Reports

---

## 🗄️ Database Details

**Database Name**

```sql
electricity_bill_management
```

### Main Tables

* admin
* consumers
* meter_readings
* bills
* payments
* notifications

---

## 📂 Project Structure

```text
Electricity_Bill_Management_System

│
├── admin/
│   ├── dashboard.php
│   ├── login.php
│   ├── manage_consumers.php
│   ├── meter_reading.php
│   ├── generate_bill.php
│   ├── payments.php
│   └── reports.php
│
├── user/
│   ├── login.php
│   ├── register.php
│   ├── dashboard.php
│   ├── bills.php
│   ├── payment_history.php
│   └── profile.php
│
├── css/
├── js/
├── images/
├── database.sql
├── config.php
├── index.php
└── README.md
```

---

## ⚙️ Installation Steps

### 1. Install XAMPP

Download and install XAMPP.

### 2. Copy Project Folder

Copy the project folder into:

```text
C:\xampp\htdocs\
```

### 3. Start Apache and MySQL

Open the XAMPP Control Panel and start:

* Apache
* MySQL

### 4. Create Database

Open **MySQL Workbench** or **phpMyAdmin**.

Create the database:

```sql
CREATE DATABASE electricity_bill_management;
```

Import the `database.sql` file.

### 5. Configure Database

Update your database credentials in the `config.php` file.

### 6. Run the Project

Open your browser:

```text
http://localhost/Electricity_Bill_Management_System/
```

---

## 🔑 Login Details

### Admin

```text
Username: admin
Password: admin123
```

### Consumer

Create a new account using the registration page and log in with your registered credentials.

---

## 📊 System Workflow

```text
Consumer Registration
        ↓
Consumer Login
        ↓
Meter Reading Update
        ↓
Bill Generation
        ↓
Bill Payment
        ↓
Payment History
        ↓
Admin Reports
```

---

## 📸 Screenshots

Include screenshots of:

* Home Page
* Consumer Registration
* Consumer Login
* Consumer Dashboard
* Bill Details
* Payment History
* Admin Login
* Admin Dashboard
* Meter Reading Management
* Bill Generation
* Reports

---

## 🚀 Future Enhancements

* Online Payment Gateway Integration
* SMS & Email Bill Notifications
* QR Code Bill Payment
* Mobile Application
* Smart Meter Integration
* AI-Based Electricity Consumption Analysis
* Monthly Usage Analytics Dashboard

---
## screenshots
<img width="1890" height="916" alt="home page" src="https://github.com/user-attachments/assets/c0635bb8-5f8d-4202-9f88-4da6aa7ee901" />
<img width="1912" height="832" alt="customer login" src="https://github.com/user-attachments/assets/a5112887-aca8-4c4c-834e-f50932d0d434" />
<img width="1907" height="910" alt="customer dashboard" src="https://github.com/user-attachments/assets/3ada34ff-e8e4-4d67-8bfe-62abdcef7cd0" />
<img width="1912" height="745" alt="customer bill" src="https://github.com/user-attachments/assets/36661112-1d79-424a-b920-06ee936fac15" />
<img width="1912" height="910" alt="admin login" src="https://github.com/user-attachments/assets/d3a15bfe-fb7c-4fce-b787-52c60ec47837" />
<img width="1912" height="932" alt="admin dashboard" src="https://github.com/user-attachments/assets/bab3c5d0-e366-498d-bd89-000fa4c2e9c4" />
<img width="1917" height="856" alt="add customer" src="https://github.com/user-attachments/assets/c1366a08-ab99-470f-9e98-311e276d6f69" />
<img width="1881" height="862" alt="generate bill" src="https://github.com/user-attachments/assets/9f32a439-e6f6-4132-9e38-f732319f42d7" />
<img width="1917" height="810" alt="total customer" src="https://github.com/user-attachments/assets/598b0b8d-210d-4b09-9871-74b2cde78d76" />
<img width="1907" height="417" alt="bill history" src="https://github.com/user-attachments/assets/5295377b-9a50-4ba5-88fa-d26b6ac92982" />



## 👩‍💻 Developer

**Divya Rahane**

BCA Science Project

---

## 📄 License

This project is developed for educational purposes only.
