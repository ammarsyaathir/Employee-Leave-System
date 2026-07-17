<div align="center">

# 🍃 Employee Leave Management System (ELMS)

### A Web-Based Employee Leave Management System

Manage employee leave applications, approvals, balances, holidays, and history through a centralized web application.

![Java](https://img.shields.io/badge/Java-17-orange?logo=openjdk)
![JSP](https://img.shields.io/badge/JSP-JakartaEE-blue)
![Servlet](https://img.shields.io/badge/Servlet-JakartaEE-success)
![MySQL](https://img.shields.io/badge/MySQL-8.0-blue?logo=mysql)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5-purple?logo=bootstrap)
![License](https://img.shields.io/badge/License-Educational-green)

</div>

---

# 📖 Overview

The **Employee Leave Management System (ELMS)** is a web-based application developed to simplify and automate the employee leave management process within an organization.

The system replaces manual leave applications by allowing employees to submit leave requests online while enabling administrators to manage employees, review applications, maintain leave balances, and monitor leave history through a centralized dashboard.

---

# ✨ Key Features

## 👨‍💼 Employee

- Login securely
- Dashboard overview
- Apply for leave
- Upload supporting documents
- Edit leave application
- Cancel leave request
- View leave history
- View leave balance
- View public holidays
- Update profile
- Change password

---

## 👨‍💼 Administrator

- Dashboard analytics
- Employee management
- Register employee
- Activate / Deactivate employee
- Review leave applications
- Approve / Reject leave
- Manage public holidays
- View all leave history
- View employee leave balances
- Employee directory
- View supporting attachments

---

# 🚀 System Architecture

```
Employee
      │
      ▼
JSP / HTML / Bootstrap
      │
      ▼
Java Servlet Controller
      │
      ▼
DAO Layer
      │
      ▼
MySQL Database
```

---

# 🛠 Technology Stack

| Technology | Description |
|------------|-------------|
| Java | Backend Programming |
| JSP | Frontend Pages |
| Servlet | Controller Layer |
| JDBC | Database Connectivity |
| MySQL | Database |
| HTML5 | Structure |
| CSS3 | Styling |
| Bootstrap | Responsive UI |
| JavaScript | Client-side Interaction |
| Apache Tomcat | Web Server |
| Eclipse IDE | Development Environment |

---

# 📂 Project Structure

```
LEAVE
│
├── src
│   ├── main
│   │   ├── java
│   │   │     ├── dao
│   │   │     ├── bean
│   │   │     ├── servlet classes
│   │   │     └── utility classes
│   │   │
│   │   └── webapp
│   │         ├── css
│   │         ├── images
│   │         ├── js
│   │         ├── WEB-INF
│   │         └── JSP Pages
│
└── Database
```

---

# 📸 System Screenshots

You can include screenshots like this.

```
README/
│
├── login.png
├── dashboard.png
├── apply_leave.png
├── leave_history.png
├── admin_dashboard.png
├── review_leave.png
└── employee_directory.png
```

Example

```md
## Login

![Login](README/login.png)

## Employee Dashboard

![Dashboard](README/dashboard.png)

## Apply Leave

![Apply](README/apply_leave.png)
```

---

# 📑 Documentation

| Document | Description | Link |
|----------|-------------|------|
| 📘 Software Requirement Specification (SRS) | Functional & Non-functional Requirements | **[View Document](https://drive.google.com/file/d/1xqE9oSlEFAA3MnhIIrkVxFUUGN-Oqyc7/view?usp=sharing)** |
| 📙 Software Design Description (SDD) | System Design & Architecture | **[View Document](https://drive.google.com/file/d/1ApZ927tb2RnOj0kYMU_SCRNmsQktkD0Y/view?usp=sharing)** |
| 📗 Software Test Design (STD) | Test Cases & Test Design | **[View Document](https://drive.google.com/file/d/1OFqwQRk1O6AGjaQa_nTEsHMe6TUfwSLi/view?usp=sharing)** |
| 📕 Software Test Report (STR) | Testing Results & Evidence | **[View Document](https://drive.google.com/file/d/1wHrNINfro0JBKtYFWDgW3dOY2jnVWbXm/view?usp=sharing)** |

---

# 🧪 Testing

The project has been tested for:

- Login Authentication
- Leave Application
- Leave Approval
- Leave Rejection
- Leave Cancellation
- Leave Editing
- Leave Balance Calculation
- Employee Registration
- Employee Status
- Holiday Management
- Attachment Upload
- Leave History
- Profile Management
- Change Password

---

# ⚙ Installation

## 1. Clone Repository

```bash
git clone https://github.com/USERNAME/EmployeeLeave.git
```

---

## 2. Import into Eclipse

```
File
→ Import
→ Existing Maven Project (or Dynamic Web Project)
```

---

## 3. Configure MySQL

Create database

```
employee_leave
```

Import SQL file.

Update

```
DatabaseConnection.java
```

```java
URL
USERNAME
PASSWORD
```

---

## 4. Deploy

Deploy using

```
Apache Tomcat 9+
```

---

## 5. Run

```
http://localhost:8080/LEAVE
```

---

# 📌 Main Modules

- Authentication
- Employee Management
- Leave Management
- Leave Balance Management
- Holiday Management
- Leave History
- Attachment Management
- User Profile
- Password Management

---

# 🔮 Future Enhancements

- Email Notifications
- Mobile Responsive Design
- Role-based Access Control
- HR Dashboard Analytics
- Calendar View
- Multi-Level Approval Workflow
- Annual Leave Auto-Credit
- Export Reports (PDF / Excel)
- REST API Integration
- Dark Mode

---

# 👨‍💻 Developed By

**Muhammad Ammar Syaathir Bin Abd Rahim**

Bachelor of Information Systems (Hons.) Information Systems Engineering

Universiti Teknologi MARA (UiTM)

---

# 📄 License

This project was developed for **academic and educational purposes**.

Commercial use is not permitted without permission.

---

<div align="center">

⭐ If you found this project useful, consider giving it a star!

</div>
