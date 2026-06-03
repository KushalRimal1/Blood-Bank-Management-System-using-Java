# 🩸 Blood Bank Management System (Java Swing + MySQL)

<p align="center">
  <b>A Desktop-Based Blood Bank Management System built using Java, Swing, and MySQL</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Java-Core%20Java-red?style=for-the-badge">
  <img src="https://img.shields.io/badge/Swing-GUI-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/MySQL-Database-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/JDBC-Connectivity-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge">
</p>

---

## 📌 Overview

The **Blood Bank Management System** is a standalone desktop application developed in **Java using Swing for GUI** and **MySQL for database management**.  

It is designed to streamline blood bank operations such as donor management, blood inventory tracking, and request handling. The system provides an intuitive interface suitable for small hospitals, clinics, or academic projects.

This project demonstrates core **Object-Oriented Programming (OOP)** concepts, **JDBC database connectivity**, and **desktop GUI development** using Swing.

---

## ✨ Features

### 🧑 Donor Management
- Add new donor details  
- Update existing records  
- View donor list in table format  
- Search donors by name, blood group, or location  
- Delete donor records  

---

### 🩸 Blood Stock Inventory
- Track available blood units for all groups:
  - A+, A-, B+, B-, AB+, AB-, O+, O-  
- Automatically update stock after donation or request  
- Real-time inventory overview  

---

### 🔍 Search Functionality
- Search donors quickly using:
  - Blood group  
  - Name  
  - Location  
- Useful for emergency requirements  

---

### 🏥 Request Management
- Handle blood requests from hospitals or individuals  
- Approve or reject requests based on availability  
- Maintain request history  

---

### 📊 Validation & Reports
- Basic eligibility checks:
  - Age validation  
  - Donation interval checks  
- Generate simple system reports  

---

### 💻 User-Friendly Interface
- Menu-driven Swing GUI  
- Forms with JTable, JButton, JTextField, JComboBox  
- Dialog-based interactions for better usability  

---

## 🛠️ Technologies Used

| Component | Technology |
|-----------|------------|
| Language  | Java (Core Java, OOP Concepts) |
| GUI       | Java Swing (JFrame, JPanel, JTable, JButton) |
| Database  | MySQL |
| Connectivity | JDBC |
| IDE       | IntelliJ IDEA |
| Libraries | MySQL Connector/J (JDBC Driver) |

---

## 🧩 Key Modules

- 👤 Donor Module  
- 🩸 Blood Inventory Module  
- 🏥 Request Management Module  
- 🔍 Search Module  
- 🛡️ Admin Control Module  

---

## 🎯 Objective

To develop a desktop-based system that simplifies blood bank operations by efficiently managing donors, blood inventory, and requests while ensuring quick access to critical data during emergencies.

---

## ⚙️ Installation Guide

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/blood-bank-java.git

# 2. Open project in IntelliJ IDEA or Eclipse

# 3. Import MySQL database
bloodbank.sql

# 4. Add MySQL JDBC Connector to project

# 5. Configure database connection in code

# 6. Run main.java
