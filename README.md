# 🏥 PATIENTS RECORD MANAGEMENT SYSTEM

## 📖 Description

The **Patients Record Management System** is a lightweight yet powerful web-based application designed to streamline the storage, retrieval, and management of patient information in clinics, hospitals, and small healthcare centers.  
It replaces traditional paper-based systems with a fast, secure, and user-friendly digital platform.

The system allows healthcare staff to easily add, view, update, and delete patient records.  
Built using **PHP, MySQL, HTML, CSS, and JavaScript**, this project is ideal for academic use, internships, and real-world healthcare environments.

This platform ensures **accuracy, accessibility, and data security**—making patient handling smoother and more efficient.

---

## ✨ Features

- 📝 **Add New Patients** → Store patient name, age, gender, medical condition, treatments, and more  
- 🔍 **Search & View Records** → Quickly search for patients by ID or name  
- ✏️ **Edit/Update Records** → Modify patient details with one click  
- ❌ **Delete Records** → Remove outdated or duplicate information  
- 📋 **Organized Medical Information** → Personal data + medical history  
- 🔒 **Secure Database Storage** → Protected PHP–MySQL backend  
- 🖥️ **Simple UI** → Clean and easy-to-use web interface  
- 🌐 **Responsive Layout** → Works smoothly on mobile, tablet, and desktop

---

## ⚙️ Technologies Used

- **Frontend:** HTML5, CSS3, JavaScript  
- **Backend:** PHP 8+  
- **Database:** MySQL 8+  
- **Server:** Apache (XAMPP)  
- **Tools/IDE:** Visual Studio Code  

---

## 🖥️ System Requirements

### 🔹 Software
- XAMPP 8.0+  
- PHP 8.0+  
- MySQL 8.0+  
- VS Code (or any code editor)

### 🔹 Hardware
- Processor: Dual-Core / Intel i3 or higher  
- RAM: 4GB minimum  
- Storage: 2GB free space  
- Works on Windows, Linux, and macOS  

---

## 🚀 Installation Guide

### 1️⃣ Clone or Download the Project
- Visit the GitHub Repository  
- Click **Code → Download ZIP**  
- Extract the folder to your computer

### 2️⃣ Move Project to XAMPP Directory
Copy the project folder to:

C:\xampp\htdocs\

markdown
Copy code

### 3️⃣ Start Services
Open **XAMPP Control Panel** → Start:
- Apache  
- MySQL  

### 4️⃣ Create the Database
1. Open browser → type `http://localhost/phpmyadmin`  
2. Click **New Database**  
3. Create database:
   ```sql
   CREATE DATABASE prmsdb;
Import the SQL file from the project's db/ folder (if provided)

5️⃣ Configure the Database Connection
Open connection.php or config.php and set:

php
Copy code
$servername = "localhost";
$username   = "root";
$password   = "";
$dbname     = "prmsdb";


6️⃣ Run the Project
Open browser and visit:

pgsql
Copy code
http://localhost/Patients-Record-Management-System/

🧪 Testing Modules
✅ Add patient

✅ Edit patient

❌ Delete patient

🔍 Search & filter patient records

🗂️ View patient medical history

📊 Validate inputs (age, phone, etc.)

👨💻 Author
Yashraj Vadagave
Patients Record Management System – PHP | MySQL | HTML | CSS
