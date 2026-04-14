# 🎓 Student Result Management System (C# + SQLite)

## 📌 Overview
The **Student Result Management System** is a console-based application developed in **C#** using **SQLite database**.  
It allows efficient management of student records, including marks entry, result calculation, and permanent data storage.

This project demonstrates core programming concepts such as **OOP, CRUD operations, database integration, and data analysis**.

---

## ✨ Features

- ➕ Add new student records
- 📋 Display all students (sorted by percentage)
- ✏️ Update existing student data
- 🔍 Search students by name
- 📊 View statistics (total, average, highest, lowest)
- 💾 Persistent storage using SQLite database

---

## 🧑‍🎓 Student Information

Each student record contains:

- Name
- Visual Programming Marks
- Compiler Construction Marks
- Numerical Analysis Marks
- Web Engineering Marks
- Cyber Security Marks

---

## 🧮 Grading System

| Percentage | Grade |
|------------|-------|
| 80 – 100   | A     |
| 60 – 79    | B     |
| 50 – 59    | C     |
| Below 50   | Fail  |

---

## 🗄️ Database Structure (SQLite)

### Table: `Students`

| Field        | Type    | Description              |
|--------------|---------|--------------------------|
| Name         | TEXT    | Primary Key              |
| VP           | INTEGER | Visual Programming       |
| CC           | INTEGER | Compiler Construction    |
| NA           | INTEGER | Numerical Analysis       |
| WE           | INTEGER | Web Engineering          |
| CS           | INTEGER | Cyber Security           |
| Total        | INTEGER | Total Marks             |
| Percentage   | REAL    | Percentage Score        |
| Grade        | TEXT    | Final Grade            |

---

## 🛠️ Technologies Used

- C# (.NET Console Application)
- SQLite Database (`Microsoft.Data.Sqlite`)
- SQL Queries
- Object-Oriented Programming (OOP)
- LINQ (for sorting & analysis)

---

## 🚀 How to Run the Project

### 1️⃣ Requirements
- Visual Studio (2022 or later)
- .NET SDK
- SQLite NuGet Package:
```bash
Microsoft.Data.Sqlite
