# Task 4 — Security Enhancements  
**Internship:** Web Development with PHP & MySQL  
**Organization:** ApexPlanet Software Pvt. Ltd.  
**Timeline:** 10 Days  

---

## 🎯 Objective
- Secure the web application against common web vulnerabilities.  
- Implement **form validation** and **user roles** for controlled access.  

---

## 🧩 Steps Implemented

### 1. Prepared Statements
- Converted all SQL queries to **prepared statements** using **MySQLi/PDO** to prevent SQL injection.  
- Ensured safe execution of user input through parameter binding and query sanitization.  

### 2. Form Validation
- Added **server-side validation** in PHP for all forms to ensure data integrity and prevent invalid input.  
- Integrated **client-side validation** using JavaScript to enhance user experience and responsiveness.  

### 3. User Roles & Permissions
- Extended the `users` table to include **role types** (e.g., `admin`, `editor`, `user`).  
- Implemented **role-based access control (RBAC)** for specific pages and actions.  
- Ensured that only authorized users can perform sensitive operations like data modification or deletion.  

---

## 🚀 Deliverables
- A more secure PHP–MySQL web application with:
  - Prepared statements for all database interactions.  
  - Proper form validation on both server and client sides.  
  - Defined user roles and permissions for controlled access.  
- Documentation outlining all implemented security measures.

---

## 🧠 Key Learnings
- Importance of using **prepared statements** to eliminate SQL injection vulnerabilities.  
- Enhanced understanding of **server vs client validation** workflows.  
- Practical experience with **role-based access control** (RBAC) in PHP.  
- Improved debugging and testing skills for security-focused features.  

---

## 🧰 Tech Stack
- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** PHP (MySQLi / PDO)  
- **Database:** MySQL  
- **Environment:** XAMPP / WAMP  

---

## ⚙️ Setup Instructions
1. Clone or download the project files into your local server directory (e.g., `htdocs`).  
2. Create a MySQL database (e.g., `secure_app_db`).  
3. Import the provided SQL file to set up tables and roles.  
4. Update `config.php` with your database credentials.  
5. Start Apache and MySQL via XAMPP/WAMP.  
6. Access the application through:  localhost/your_folder.php
