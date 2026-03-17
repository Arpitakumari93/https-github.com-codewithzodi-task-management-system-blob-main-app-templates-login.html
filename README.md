🌟 Project Overview
Task Management System is a Full Stack Web Application designed to manage daily workflow efficiently.

The system supports multi-user authentication, task tracking, and a powerful admin dashboard with full system control.

✅ Secure Login System
✅ User Task Management
✅ Admin Control Panel
✅ Premium Dashboard UI

🏗️ MVC Architecture
Model → MySQL Database View → HTML + Bootstrap Templates Controller → Flask Routes

🛠️ Tech Stack
🔹 Backend
Python
Flask Framework
🔹 Frontend
HTML5
Bootstrap 5
Jinja2 Templates
Font Awesome Icons
🔹 Database
MySQL
🔹 Version Control
Git & GitHub

👤 User Features
✅ User Registration & Login
✅ Password Hashing Security
✅ Create Tasks
✅ View Personal Tasks
✅ Update Tasks
✅ Delete Tasks
✅ Search Tasks
✅ Status Tracking

👑 Admin Panel
Admin Login
admin@gmail.com
password
Admin Capabilities:
✅ View All Users
✅ Monitor All Tasks
✅ Edit Any Task
✅ Delete Any Task
✅ System Dashboard
✅ Task Statistics

📋 Task Attributes
Attribute	Description
Title	Task Name
Description	Task Details
Due Date	Deadline
Status	Pending / Progress / Completed
Remarks	Notes
Created On	Timestamp
Updated On	Timestamp
Created By	User
Updated By	User

🗄️ Database Design
📌 ER Diagram
The system follows a relational database structure where each user can create and manage multiple tasks.

ER Diagram

📖 Data Dictionary
Users Table
Column Name	Data Type	Description
id	INT (PK)	Unique User Identifier
name	VARCHAR(100)	User Full Name
email	VARCHAR(100)	User Email
password	VARCHAR(255)	Encrypted Password
role	VARCHAR(20)	User Role (Admin/User)
Tasks Table
Column Name	Data Type	Description
id	INT (PK)	Unique Task Identifier
title	VARCHAR(255)	Task Title
description	TEXT	Task Description
due_date	DATE	Task Deadline
status	VARCHAR(50)	Task Status
remarks	TEXT	Additional Notes
created_on	DATETIME	Creation Timestamp
updated_on	DATETIME	Last Updated Timestamp
created_by	INT (FK)	Task Creator ID
updated_by	INT (FK)	Last Updater ID

⚡ Index Documentation
Primary Key indexing is applied on id fields for faster record retrieval.
Foreign Key indexing is implemented on created_by and updated_by.
Search operations are optimized using indexed task title and status fields.

🔐 Authentication System
Session Based Authentication
Secure Password Hashing (Werkzeug)
Route Protection
Admin Authorization

🎨 Premium UI Features
✨ Modern Dashboard
✨ Bootstrap Cards
✨ Responsive Layout
✨ Status Badges
✨ Admin Analytics View
✨ Clean Navigation

