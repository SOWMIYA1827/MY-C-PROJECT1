🏪 Department Store Management System
📌 Overview
A comprehensive C-based Department Store Management System that allows efficient management of products, customers, and sales transactions. This console application provides a user-friendly interface for store administrators to handle daily operations seamlessly.

✨ Features
📦 Product Management
Add New Products - Store product details including name, price, quantity, and category

Display All Products - View complete product inventory in formatted tables

Search Products - Find products by ID or name with partial matching

Update Product Quantity - Modify stock levels easily

👥 Customer Management
Add New Customers - Register customers with contact information

Display All Customers - View customer database with spending history

Customer Tracking - Monitor total amount spent by each customer

💰 Sales & Transactions
Process Sales - Complete purchase transactions with real-time inventory updates

Receipt Generation - Automatic receipt creation with itemized billing

Stock Validation - Prevent sales when inventory is insufficient

📊 Reporting System
Inventory Reports - View total inventory value and product count

Low Stock Alerts - Identify items with stock below threshold (less than 10)

Customer Statistics - Track total registered customers

💾 Data Persistence
Auto-save/Load - Automatic data preservation between sessions

File Storage - All data stored in store_data.txt for reliability

Data Integrity - Ensures no data loss on program exit

🛠️ Technical Implementation
Data Structures
c
struct Product {
    int id;
    char name[50];
    float price;
    int quantity;
    char category[30];
};

struct Customer {
    int id;
    char name[50];
    char phone[15];
    float totalSpent;
};
Core Functions
main() - Program entry point with menu-driven interface

processSale() - Handles complete transaction workflow

saveData()/loadData() - File I/O operations for data persistence

generateReport() - Business intelligence and analytics

🚀 How to Compile and Run
Prerequisites
GCC Compiler (MinGW for Windows, GCC for Linux/Mac)

Basic C development environment

Compilation
bash
gcc PROGRAM1.c -o store_management.exe  # Windows
gcc PROGRAM1.c -o store_management      # Linux/Mac
Execution
bash
./store_management.exe  # Windows
./store_management      # Linux/Mac
📋 Menu Options
Add New Product - Expand your product catalog

Display All Products - View complete inventory

Search Product - Find specific items quickly

Update Product Quantity - Adjust stock levels

Add New Customer - Register new shoppers

Display All Customers - Review customer database

Process Sale - Complete purchase transactions

Generate Report - View business insights

Save Data - Manual data backup

Exit - Safely close the application

💡 Key Features in Detail
🔍 Intelligent Search
ID-based Search - Direct access using unique product identifiers

Name-based Search - Partial string matching for flexible searching

🛒 Sales Processing
Multi-item Purchases - Add multiple products in single transaction

Real-time Updates - Inventory reduces automatically after sales

Customer Tracking - Updates customer's lifetime spending

📈 Reporting Capabilities
Inventory Valuation - Calculates total value of all stock

Stock Alerts - Highlights items needing restocking

Business Metrics - Provides overview of store operations

🔒 Data Management
Storage Format
Text-based Storage - Human-readable store_data.txt file

Structured Format - Organized data layout for easy debugging

Automatic Loading - Previous session data loads on startup

Data Security
Auto-save on Exit - Prevents data loss

Manual Save Option - User-controlled backups

Error Handling - Graceful handling of file operations

🎯 Business Benefits
For Store Owners
Efficient Inventory Management - Track stock levels accurately

Customer Relationship Management - Build customer loyalty through tracking

Sales Analytics - Make informed business decisions

For Staff
User-Friendly Interface - Minimal training required

Quick Operations - Fast product lookup and sales processing

Error Reduction - Automated calculations minimize mistakes

📁 File Structure
text
PROGRAM1.c              # Main source code
store_data.txt          # Auto-generated data file (created on first run)
README.md              # This documentation
