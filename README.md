# TA Management System  
### Streamlining University Teaching Assistant Operations

A modern full-stack web platform that centralizes Teaching Assistant (TA) assignment, tracking, and performance monitoring in one secure system.

Built to replace inefficient spreadsheets and manual coordination with a structured, role-based solution.

---
## Demo

Watch the demo here:  
[Click to view the demo](https://drive.google.com/file/d/17bITf8onCUGt7ElE4dPyIg_tiLo0cvsT/view?usp=sharinghttps://drive.google.com/file/d/17bITf8onCUGt7ElE4dPyIg_tiLo0cvsT/view?usp=sharing)

---

## Why This Project?

University courses often manage TAs manually, leading to:

- Poor visibility on workload  
- No centralized performance tracking  
- Inefficient communication  
- Security concerns with shared documents  

This platform solves those issues through a secure, database-driven web system.

---

## Core Features

### Secure Authentication
- Login system with session management  
- Role-based access control  

### Role-Based Dashboards
Separate dashboards for:
- Manager  
- Instructor  
- Teaching Assistant  

Each role sees only relevant data and actions.

### Smart Task Management
- Assign tasks to TAs  
- Update task status  
- Track completion progress  

### Working Hours Tracking
- Log TA hours  
- Monitor workload distribution  

### Performance Monitoring
- Track activity and engagement  
- Evaluate task completion rates  

### Responsive UI
Optimized for both desktop and mobile use.

---

## Architecture Overview

**Frontend**  
HTML5 · CSS3 · JavaScript  

**Backend**  
PHP (Server-side logic & session handling)  

**Database**  
MySQL (Relational data storage)  

**Flow:**  
User → Web Interface → PHP Backend → MySQL Database → Response Rendering

---

## Project Structure

```bash
Full_Stack_TA_Management_Website/
├── assets/              # Images and static files
├── css/                 # Stylesheets
├── js/                  # JavaScript logic
├── includes/            # Reusable PHP components
├── config.php           # Database configuration
├── index.php            # Authentication entry point
├── dashboard.php        # Role-based dashboards
└── database.sql         # Database schema
```

---

## Tech Stack

| Layer       | Technology |
|------------|------------|
| Frontend   | HTML, CSS, JavaScript |
| Backend    | PHP |
| Database   | MySQL |
| Version Control | Git & GitHub |

---

## Local Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/Ahmed-BinHelabi/Full_Stack_TA_Management_Website.git
cd Full_Stack_TA_Management_Website
```

### 2️⃣ Backend Setup

- Install XAMPP or WAMP  
- Import `database.sql` into MySQL  
- Update credentials in `config.php`  

Example:

```php
$host = "localhost";
$user = "root";
$password = "";
$database = "ta_management";
```

### 3️⃣ Run Project

Start Apache & MySQL, then open:

```
http://localhost/Full_Stack_TA_Management_Website/
```

---

## Security Highlights

- Session-based authentication  
- Role-restricted routes  
- Protected backend logic  

---

## Future Roadmap

- REST API implementation  
- Email notifications for task updates  
- Analytics dashboard with charts  
- Cloud deployment  
- UI/UX redesign  

---

## Author

Ahmed Bin Halabi  
Software Engineering Student — Alfaisal University   
[GitHub](https://github.com/Ahmed-BinHelabi) | [LinkedIn](https://www.linkedin.com/in/your-linkedin-username/)
