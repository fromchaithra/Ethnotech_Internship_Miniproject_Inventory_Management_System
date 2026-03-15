# Ethnotech_Internship_Miniproject_Inventory_Management_System
# Inventory Management System (Java + Swing + MongoDB)

## 📌 Project Overview

The **Inventory Management System** is a desktop application developed using **Java Swing** for the graphical user interface and **MongoDB** as the database.
This system allows users to manage product records efficiently by performing basic **CRUD operations (Create, Read, Update, Delete)**.

The project was developed as part of an **internship mini project** to demonstrate the integration of **Java GUI applications with a NoSQL database**.

---

## 🛠 Technologies Used

* **Java** – Core programming language
* **Java Swing** – Graphical User Interface (GUI)
* **MongoDB** – NoSQL database
* **MongoDB Java Driver** – Database connectivity
* **NetBeans / Eclipse** – Development IDE
* **Git & GitHub** – Version control

---

## ✨ Features

* Login authentication system
* Add new product records
* View products in a table
* Update existing product information
* Delete product records
* MongoDB database connectivity
* User-friendly desktop interface

---

## 🖥 System Modules

1. **Login Module**

   * Validates user credentials before accessing the system.

2. **Product Management**

   * Add product details
   * Update product information
   * Delete product records
   * Display products using JTable

3. **Database Connection**

   * Connects Java application with MongoDB database.

---

## 📂 Project Structure

```
InventoryManagementSystem
│
├── LoginPage.java
├── InventorySystem.java
├── MongoDBConnection.java
└── README.md
```

---

## 🗄 Database Structure

Database Name:

```
InventoryDB
```

Collection:

```
products
```

Example Document:

```json
{
  "productId": "P101",
  "name": "Laptop",
  "category": "Electronics",
  "quantity": 10,
  "price": 55000
}
```

---

## ⚙️ Installation & Setup

### 1️⃣ Install MongoDB

Download and install MongoDB from:
https://www.mongodb.com/try/download/community

Start MongoDB server.

---

### 2️⃣ Clone the Repository

```
git clone https://github.com/yourusername/inventory-management-system.git
```

---

### 3️⃣ Add MongoDB Java Driver

Download MongoDB Java Driver and add the JAR files to your project libraries.

Required JARs:

* mongodb-driver-sync
* mongodb-driver-core
* bson

---

### 4️⃣ Run the Project

Run:

```
LoginPage.java
```

---

## 🔑 Login Credentials

```
Username : admin
Password : admin123
```

---

## 📸 Screenshots

(Add screenshots of your login page and dashboard here)

---

## 🎯 Learning Outcomes

* Understanding of Java Swing GUI development
* Integration of Java applications with MongoDB
* Implementation of CRUD operations
* Practical experience with NoSQL databases
* Version control using Git and GitHub

---

## 📚 Future Enhancements

* Product search functionality
* Report generation
* User role management
* Improved dashboard UI
* Export inventory data to Excel

---

## 👩‍💻 Author

Developed as part of an **Internship Mini Project**.

---

## 📄 License

This project is for **educational purposes**.
