Student Result Management System (C# + SQLite)
📌 Project Overview

This is a Console-Based Student Result Management System built in C# using SQLite database.
It allows users to manage student records, calculate results, and store data permanently in a database.

🚀 Features
➕ Add new student with marks
📋 View all students (sorted by percentage)
✏️ Update student records
🔍 Search student by name
📊 View statistics (average, highest, lowest, total students)
💾 Permanent data storage using SQLite database
🧑‍🎓 Student Data Structure

Each student contains:

Name
Visual Programming marks
Compiler Construction marks
Numerical Analysis marks
Web Engineering marks
Cyber Security marks
🧮 Calculations
Total Marks = Sum of 5 subjects
Percentage = Total / 5
Grade System:
80+ = A
60–79 = B
50–59 = C
Below 50 = Fail
🗄️ Database (SQLite)
Table: Students
Column	Type
Name	TEXT (Primary Key)
VP	INTEGER
CC	INTEGER
NA	INTEGER
WE	INTEGER
CS	INTEGER
Total	INTEGER
Percentage	REAL
Grade	TEXT
⚙️ Technologies Used
C# (.NET Console Application)
SQLite (Microsoft.Data.Sqlite)
LINQ (for sorting and logic)
OOP (Object-Oriented Programming)
📂 How to Run Project
1️⃣ Install Requirements
Visual Studio
.NET SDK
SQLite package:
Microsoft.Data.Sqlite
2️⃣ Run Project
Open project in Visual Studio
Build solution
Run program (Start)
3️⃣ Database File

SQLite automatically creates:

StudentDb.db

in the project output folder:

bin/Debug/
📌 Main Menu Options
Add Student
Show Students
Update Student
Search Student
Statistics
Exit
💡 Key Learning Points
Database connectivity in C#
CRUD operations (Create, Read, Update)
SQL queries inside C#
Data persistence using SQLite
Console UI design
👨‍💻 Author

This project is developed for learning purposes to understand:

C# programming
Database integration
Real-world CRUD systems
📌 Future Improvements
Delete student feature
Login system (Admin/Teacher)
GUI version (Windows Forms / WPF)
Export to Excel/PDF
Online cloud database integration
⭐ Conclusion

This is a beginner-friendly but powerful Student Management System with full database support using SQLite.
