# Java Library Management System 📚

A robust, console-based application built with **Java** and **SQL** to automate the workflow of a modern library. This project focuses on efficient data handling, clean code architecture, and CRUD operations.

## 🚀 Features
- **Inventory Management:** Add, update, and remove book records from the database.
- **Member System:** Register new members and track their borrowing history.
- **Search Engine:** Search books by Title, Author, or ISBN using optimized SQL queries.
- **Transaction Logic:** Real-time tracking of book availability and automated fine calculation.

## 🛠 Tech Stack
- **Language:** Java (JDK 17+)
- **Database:** SQL (MySQL/PostgreSQL)
- **Tools:** JDBC (Java Database Connectivity), Git, Maven

## 📂 Project Architecture
The system follows Object-Oriented Programming (OOP) principles:
- **Encapsulation:** Used for Book and User models to ensure data security.
- **Abstraction:** Used for database operations to decouple logic from the UI.
- **Inheritance:** Implemented for different user types (Librarian vs. Member).

## 📊 Database Schema
The project utilizes a relational database with the following primary tables:
- `Books`: (ISBN, Title, Author, Quantity, Status)
- `Users`: (UserID, Name, Email, MembershipType)
- `Transactions`: (TransactionID, BookID, UserID, IssueDate, DueDate)

## 🔧 Installation & Setup
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/yourusername/library-management-java.git](https://github.com/yourusername/library-management-java.git)
