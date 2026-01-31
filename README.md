# 🍽️ Restaurant Management System

## 📌 Project Overview
The Restaurant Management System is a web-based application that helps restaurants manage table reservations, customer orders, and billing efficiently. Customers can view real-time table availability and reserve tables, while staff can manage reservations, add dishes to tables, generate bills, and complete checkout operations.

---

## 🎯 Features

### Customer Module
- View available and booked tables
- Reserve tables online
- Color-based table status  
  - 🟢 Green = Available  
  - 🔴 Red = Booked  

### Staff/Admin Module
- View all reservations
- Manage table occupancy
- Add food items to table orders
- Update quantities and orders
- Generate automatic bills
- Process checkout

---

## ⚙️ Technologies Used

- Frontend: HTML, CSS, JavaScript  
- Backend: PHP  
- Database: MySQL  
- Server: XAMPP (Apache & MySQL)

---

## 🏗️ System Workflow

1. Customer checks table availability  
2. Customer books a table  
3. Table status updates in real time  
4. Staff views reservations  
5. Orders are added to table  
6. Bill is generated  
7. Checkout is completed  

---

## 🚀 Installation Steps (XAMPP)

1. Install XAMPP  
2. Start Apache and MySQL from XAMPP Control Panel  
3. Copy the project folder to:
   C:\xampp\htdocs\  
4. Open browser and go to:
   http://localhost/phpmyadmin  
5. Import the database `.sql` file  
6. Open the project:
   http://localhost/your_project_folder_name  

---

## 🛠️ Database Configuration

Update your database connection file (example: `config.php` or `db.php`):

```php
$servername = "localhost";
$username = "root";
$password = "";
$database = "restaurant_db";
```

---

## 📈 Benefits

- Real-time table management  
- Faster order processing  
- Automated billing system  
- Reduced manual errors  
- Improved customer experience  

---

## 👨‍💻 Developed By

Your Name  Pranav Thanavel
B.Tech Computer Science & Engineering  

---

## 📄 License

This project is for educational purposes only.
