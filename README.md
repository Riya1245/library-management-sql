# 📚 Library Management System - SQL Project

## 🔹 Description:
This project represents a Library Management System designed using SQL. It includes the creation of five well-structured tables with appropriate primary and foreign keys, representing real-world entities and relationships.

## 🗃️ Tables:
- **Authors**: Stores author information
- **Categories**: Contains book categories (genres)
- **Books**: Holds book details with references to authors and categories
- **Members**: Library users who borrow books
- **Borrow**: Tracks book borrow and return activity

## 🔗 Relationships:
- One Author can write many Books
- Each Book belongs to one Category
- One Member can borrow many Books
- Borrow table links Members and Books

## 📸 ER Diagram:
![ER Diagram](ER_Diagram.png)

## 💾 Tools Used:
- MySQL Workbench – for writing and executing SQL queries
- dbdiagram.io – for visualizing the ER Diagram
- GitHub – for version control and submission

## 📁 Files Included:
- `schema.sql` – Contains all the SQL commands for creating and populating the tables
- `ER_Diagram.png` – Entity-Relationship diagram showing table structure
- `README.md` – This file, explaining the project structu
