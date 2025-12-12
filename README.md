# 🏬 Department Store Management System

[![GitHub Pages](https://img.shields.io/badge/Live-Demo-brightgreen)](https://sowmiya1827.github.io/MY-C-PROJECT1/)
[![C Language](https://img.shields.io/badge/C-00599C?logo=c&logoColor=white)](https://en.wikipedia.org/wiki/C_(programming_language))
[![File Handling](https://img.shields.io/badge/File-Handling-blue)](https://en.cppreference.com/w/c/io)
[![Console App](https://img.shields.io/badge/Console-Application-yellow)](https://en.wikipedia.org/wiki/Console_application)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## 🚀 **Live Demo & Repository**
🌐 **Live Website**: [https://sowmiya1827.github.io/MY-C-PROJECT1/](https://sowmiya1827.github.io/MY-C-PROJECT1/)

📂 **GitHub Repository**: [https://github.com/SOWMIYA1827/MY-C-PROJECT1](https://github.com/SOWMIYA1827/MY-C-PROJECT1)

---

## 📖 **Project Overview**

A **complete Department Store Management System** developed in **C Programming Language**. This console-based application helps store managers efficiently manage products, customers, sales, and inventory with **persistent data storage** capability.

### **🎯 Key Features:**
- ✅ **Product Management** - Add, view, search, update products
- ✅ **Customer Management** - Maintain customer database
- ✅ **Sales Processing** - Handle customer purchases and generate receipts
- ✅ **Inventory Tracking** - Real-time stock updates
- ✅ **Data Persistence** - Save/load data to/from files
- ✅ **Reporting System** - Generate store performance reports
- ✅ **User-Friendly Console Menu** - Intuitive navigation

---

## 🛠️ **Technology Stack**

### **🔧 Core Technologies:**
| Component | Technology | Purpose |
|-----------|------------|---------|
| **Programming Language** | **C Language** | Core application logic and algorithms |
| **Data Storage** | **File Handling** | Persistent data storage using text files |
| **Data Structures** | **Struct Arrays** | Product and customer data management |
| **Input/Output** | **Standard I/O** | Console-based user interface |
| **Memory Management** | **Static Arrays** | Fixed-size data storage |

### **📚 Libraries Used:**

#include <stdio.h>    // Standard Input/Output operations
#include <string.h>   // String manipulation functions
#include <stdlib.h>   // Standard library functions
🧩 Key Data Structures:
c
// Product Structure
struct Product {
    int id;
    char name[50];
    float price;
    int quantity;
    char category[30];
};

// Customer Structure
struct Customer {
    int id;
    char name[50];
    char phone[15];
    float totalSpent;
};
📊 System Architecture
text
DEPARTMENT STORE MANAGEMENT SYSTEM
├── 📁 Data Storage Layer
│   ├── Products Database (store_data.txt)
│   ├── Customers Database (store_data.txt)
│   └── Sales Records
│
├── 🔧 Business Logic Layer
│   ├── Product Management Module
│   ├── Customer Management Module
│   ├── Sales Processing Module
│   └── Reporting Module
│
└── 🖥️ Presentation Layer
    └── Console User Interface
        ├── Text-based Menu System
        └── Formatted Output Display
🎮 Features in Detail
1. 📦 Product Management
Add New Products with details (ID, name, price, quantity, category)

View All Products in formatted table display

Search Products by ID or name

Update Product Quantity for stock management

2. 👥 Customer Management
Add New Customers with contact information

View Customer Database with purchase history

Track Customer Spending for loyalty insights

3. 💳 Sales Processing
Process Customer Purchases with real-time stock deduction

Generate Detailed Receipts with itemized billing

Multiple Product Selection in single transaction

Stock Validation to prevent overselling

4. 📈 Reporting System
Inventory Summary - Total products and value

Low Stock Alerts - Items with quantity < 10

Customer Statistics - Total customers and their spending

5. 💾 Data Persistence
Automatic Data Save on exit

Data Loading on startup

Text File Storage for easy backup and recovery
