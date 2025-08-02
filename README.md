# Crime Management System

The Crime Management System is a web-based application developed using Django. It allows users to file FIRs, and enables police officials to manage and track cases efficiently. This project is intended to simplify crime reporting and case handling for better transparency and accountability.

---

## Features

- User registration and login
- FIR complaint filing by citizens
- Case management by police officers
- Complaint status tracking
- Admin panel for managing users and permissions
- Role-based access (User, Police, Admin)
- Dashboard with case statistics

---

## User Roles and Credentials

The system supports three types of users:

| Role    | Description                        | Default Credentials                           |
|---------|------------------------------------|-----------------------------------------------|
| User    | Can register, file, and view FIRs  | `kavya@gmail.com` / `Kavya@123`               |
| Police  | Can view and manage assigned cases | `padmakumarr@gmail.com` / `	Padmakumar123`   |

---

## Technologies Used

- **Frontend:** HTML, CSS, Bootstrap, JavaScript
- **Backend:** Python, Django
- **Database:** SQLite (default)
- **Others:** Django Admin, Django Templates

---

## Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/VineethaCodes/crime-management-system.git
   cd crime-management-system
