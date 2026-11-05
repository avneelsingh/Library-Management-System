# 📚 Library Management System

The **Library Management System (LMS)** is developed to transform manual library operations into an automated online system. It provides essential features for managing students, books, categories, and publications efficiently.

✨ **Key Features:**
- 👨‍💼 Admin and Student modules with separate functionalities.
- 📖 Add, manage, and maintain book records.
- 👨‍🎓 Student registration and account management.
- 🔐 Login authentication and basic verification-code checks.
- 📚 Book issuing, returning, and request management.
- 💰 Fine calculation and overdue book management.
- 📊 Generate user-wise and overdue reports.
- 👤 Profile management and password updates.

---

# 🚀 Getting Started

Follow these instructions to set up and run the project on your local machine for development and testing.

## 🛠️ Prerequisites

Basic knowledge of the following technologies is helpful:

- 🌐 HTML
- 🎨 CSS
- ⚙️ PHP
- 🗄️ MySQL

**XAMPP Server** is used to provide the Apache web server and MySQL database environment.

📥 Download and install XAMPP from:

https://www.apachefriends.org/download.html

## ⚙️ Setting Up the Environment

Follow these steps to run the project:

1. 📦 Download and extract the project source code on your local machine.
2. 📁 Rename the extracted folder to `lms`.
3. 📂 Move the `lms` folder into the XAMPP `htdocs` directory. The default Windows path is:

   `C:\xampp\htdocs`

4. ▶️ Open the XAMPP Control Panel and start **Apache** and **MySQL** services.
5. 🌐 Open your browser and navigate to:

   `http://localhost/phpmyadmin/`

6. 🗄️ Create a new database named `library`.
7. 📥 Select the `library` database and import the SQL file provided in the repository: `library.sql`.
8. 🔧 Open the configuration files in both `includes` directories and update the database username and password according to your local setup.
9. 🚀 Open your browser and navigate to:

   `http://localhost/lms/`

10. 🔑 Use the following default demonstration credentials to access the admin panel:

   - **Username:** `admin`
   - **Password:** `admin`
   - **Verification Code:** `12345`

⚠️ **Note:** These are demonstration credentials and the fixed verification code used in the current implementation. Change the default credentials and improve password security before deploying the application for real-world use.

---

# 📸 Screenshots

Explore the different modules and interfaces of the Library Management System.

### 🔐 Login Page

![Login Page](Screenshots/Login.png)

---

### 📊 Admin Dashboard

![Admin Dashboard](Screenshots/admin_dashboard.png)

---

### 👤 User Profile

![Profile](Screenshots/profile.png)

---

### ➕ Add Book

![Add Book](Screenshots/add_book.png)

---

### 📚 Manage Books

![Manage Books](Screenshots/manage_books.png)

---

### 🏷️ Add Category

![Add Category](Screenshots/add_category.png)

---

### 📋 Manage Categories

![Manage Category](Screenshots/manage_categories.png)

---

### 🏢 Add Publication

![Add Publication](Screenshots/add_publication.png)

---

### 📖 Manage Publications

![Manage Publication](Screenshots/manage_publications.png)

---

### 🔑 Change Password

![Change Password](Screenshots/change_password.png)

---

### 💰 Set Fine

![Set Fine](Screenshots/set_fine.png)

---

### 📕 Issue Book

![Issue Book](Screenshots/issue_book.png)

---

### 📚 Manage Issued Books

![Manage Issued Books](Screenshots/manage_issued_books.png)

---

### 📚 Manage Issued Books – View 2

![Manage Issued Books 2](Screenshots/manage_issued_books2.png)

---

### 📩 Manage Requested Books

![Manage Requested Books](Screenshots/manage_requested_books.png)

---

### 👨‍🎓 Registered Students

![Registered Students](Screenshots/registered_students.png)

---

### 📊 Reports

![Report](Screenshots/report.png)

---

### ⏰ Overdue Report

![Overdue Report](Screenshots/overdue_report.png)

---

### 👥 User-Wise Report

![User-Wise Report](Screenshots/User_wise.png)

---


