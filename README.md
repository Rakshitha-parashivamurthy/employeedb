# Java JDBC – Employee Database App

## Objective
A simple Java console-based application to perform **CRUD operations** (Create, Read, Update, Delete) on an **Employee database** using **JDBC** with **MySQL** (via XAMPP).

---

##  Technologies Used
- Java (JDK 8 or above)
- MySQL (via XAMPP)
- JDBC
- VS Code / IntelliJ / Any Java IDE

---

## Features
-  Add a new employee
-  View all employees
-  Update employee details
-  Delete employee by ID

---

## Database Setup

### 1. Start MySQL using XAMPP
- Open **XAMPP Control Panel**
- Start **Apache** and **MySQL**

### 2. Create Database & Table
1. Go to [http://localhost/phpmyadmin](http://localhost/phpmyadmin)
2. Run the following SQL code:

```sql
CREATE DATABASE EmployeeDB;

USE EmployeeDB;

CREATE TABLE employees (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(100),
    department VARCHAR(100),
    salary DOUBLE
);
