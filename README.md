🎓 Full-Stack TA Management System

A role-based web application designed to streamline the management of Teaching Assistants (TAs) in university courses.
The system enables managers and instructors to assign tasks, track working hours, and monitor performance, while providing TAs with a structured interface to manage responsibilities efficiently.

🧠 Problem Statement

Managing Teaching Assistants manually through spreadsheets or emails can lead to inefficiencies, poor tracking, and lack of transparency.
This system centralizes TA management into one secure platform with role-based access control and real-time data handling.

🚀 Key Features

🔐 Secure Authentication System
User login with password protection and session management.

👥 Role-Based Dashboards
Separate interfaces for:

Manager

Instructor

Teaching Assistant

📋 TA Assignment & Task Tracking
Assign tasks, update progress, and monitor completion status.

⏱️ Working Hours Tracking
Log and track TA working hours per course.

📊 Performance Monitoring
Evaluate TA activity and task fulfillment.

📱 Responsive Design
Compatible with desktop and mobile devices.

🏗️ System Architecture

The system follows a traditional full-stack web architecture:

Frontend (HTML, CSS, JavaScript)
Handles UI rendering and user interaction.

Backend (PHP)
Processes requests, manages sessions, enforces access control, and handles business logic.

Database (MySQL)
Stores users, roles, tasks, and tracking data.

Flow:
User → Web Interface → PHP Backend → MySQL Database → Response to User

🗂️ Project Structure

<pre> ```bash full_stack_ta_management_website/ ├── assets/ # Images and static files ├── css/ # Stylesheets ├── js/ # JavaScript files ├── includes/ # Reusable PHP components ├── config.php # Database configuration ├── index.php # Login page ├── dashboard.php # Role-based dashboards └── database.sql # Database schema ``` </pre>


🛠️ Technologies Used

Frontend

HTML5

CSS3

JavaScript

Backend

PHP

Database

MySQL

Version Control

Git & GitHub

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/Ahmed-BinHelabi/full_stack_ta_management_website.git

2️⃣ Navigate to the Project Directory
cd full_stack_ta_management_website

3️⃣ Backend Setup

Install PHP and MySQL
(You may use XAMPP or WAMP for local development.)

Import the provided database.sql file into MySQL.

Update database credentials inside config.php.

Example:

$host = "localhost";
$user = "root";
$password = "";
$database = "ta_management";

4️⃣ Run the Project

Start Apache & MySQL (if using XAMPP/WAMP).

Open http://localhost/full_stack_ta_management_website/ in your browser.

🔒 Security Considerations

Password-protected authentication

Role-based access control

Session handling to prevent unauthorized access

📈 Future Improvements

Email notifications for task updates

Advanced analytics dashboard

REST API version of the system

Deployment to cloud platforms

Improved UI/UX enhancements

👨‍💻 Author

Ahmed Bin Halabi
Software Engineering Student — Alfaisal University

[GitHub](https://github.com/Ahmed-BinHelabi)  
[LinkedIn](https://www.linkedin.com/in/ahmed-bin-halabi-a78127253/)
