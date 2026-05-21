📌 Project Overview

This database system simulates the core business processes of a large-scale e-commerce platform, including:

User management
Seller management
Product & variant management
Shopping cart system
Transactions & payment services
Delivery & logistics
Messaging system
Voucher & discount systems
Order processing
Activity tracking

The project emphasizes relational database design, data integrity, and complex SQL reporting.

🛠️ Technologies Used

MySQL
SQL
phpMyAdmin
ERD Design
Relational Database Modeling
🧩 Main Database Entities

The system contains multiple interconnected entities, including:

👤 User & Seller System

Users
Sellers
Addresses
Provinces
Cities
Districts

🛍️ E-Commerce System

Products
Variants
Categories
Carts
Orders
Transactions

💳 Payment System

Payment Methods
Payment Services
Vouchers
Discounts

🚚 Delivery System

Delivery Services
Delivery Types
Delivery Employees
Conversation Delivery

💬 Communication System

Conversations
Messages
Activities

📂 Project Structure

Shopee-Database-System/
 ├── database/
 │    ├── create_tables.sql
 │    ├── insert_data.sql
 │    ├── reports.sql
 │    └── erd.png
 ├── documentation/
 │    └── project_report.pdf
 ├── screenshots/
 ├── README.md

 🧠 Database Features
 
✅ Core Features
Relational database schema
Foreign key constraints
Transaction records
Product variant system
Voucher & discount mechanism
Cart & checkout workflow
User-seller communication
Delivery service integration

✅ Advanced Features
Complex SQL reports
Sales analytics
Transaction duration analysis
Discount ranking
Customer membership analysis
Chat response analytics

📊 SQL Reporting Features

This project includes analytical SQL queries such as:

Top 10 best-selling products
Transactions completed in under 7 days
Sellers with unfinished transactions
Delivery processes exceeding 5 days
Users eligible for platinum membership
Most desired products in carts
Chat response time analysis
Top discounted product variants

📈 Example Reports

📌 Top Selling Products

Analyze the most purchased products during 2024.

📌 Membership Upgrade Analysis

Identify users eligible for Platinum membership based on transaction value.

📌 Delivery Performance

Track transactions with delivery delays exceeding 5 days.

📌 Messaging Analytics

Analyze read-response duration between users and sellers.

🗂️ ERD Design

The database design consists of multiple normalized relational tables with interconnected foreign keys to maintain consistency and scalability.

Recommended entities include:

Users
Orders
Transactions
Products
Variants
Messages
Delivery Services

⭐ Future Improvements

Stored procedures
Database indexing optimization
Trigger implementation
Real-time analytics dashboard
API integration
Database performance optimization
