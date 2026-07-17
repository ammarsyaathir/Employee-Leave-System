<div align="center">

# 🍃 Employee Leave Management System (ELMS)

### A Web-Based Employee Leave Management System

Manage employee leave applications, approvals, balances, holidays, and history through a centralized web application.

![Java](https://img.shields.io/badge/Java-17-orange?logo=openjdk)
![JSP](https://img.shields.io/badge/JSP-JakartaEE-blue)
![Servlet](https://img.shields.io/badge/Servlet-JakartaEE-success)
![Oracle](https://img.shields.io/badge/Oracle-Database-red?logo=oracle)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5-purple?logo=bootstrap)
![License](https://img.shields.io/badge/License-Educational-green)
![MVC](https://img.shields.io/badge/Architecture-MVC-success)
![DAO](https://img.shields.io/badge/Pattern-DAO-blue)

</div>

---

## 📖 Overview

The **Employee Leave Management System (ELMS)** is a web-based application developed to simplify and automate the employee leave management process within an organization.

The system follows the **MVC (Model-View-Controller)** architecture using Java Servlets, JSP, JavaBeans, and the **DAO** design pattern with Oracle Database. It enables employees to submit leave requests, managers to review and approve requests, and administrators to manage employees, leave records, holidays, and system information through a centralized dashboard.

---

## ✨ Key Features

### 👨‍💼 Employee

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

### 🛡️ Administrator

- Dashboard analytics
- Employee management
- Register employee
- Activate / deactivate employee
- Review leave applications
- Approve / reject leave
- Manage public holidays
- View all leave history
- View employee leave balances
- Employee directory
- View supporting attachments

### 👔 Manager

- Dashboard overview
- Review leave applications
- Approve leave
- Reject leave
- View supporting documents
- Monitor employee leave
- View leave history

---

## 🚀 System Architecture

```text
Employee / Manager / Administrator
                │
                ▼
       JSP • HTML • CSS
   Bootstrap • JavaScript
                │
                ▼
      Java Servlet Controller
                │
                ▼
         JavaBean (Model)
                │
                ▼
         DAO (Data Access)
                │
                ▼
         Oracle Database
```

---

## 🛠 Technology Stack

| Technology | Description |
|------------|-------------|
| Java 17 | Backend |
| JSP | Dynamic web pages |
| Jakarta Servlet | Controller |
| JavaBean | Model |
| DAO Pattern | Database access |
| JDBC | Database connectivity |
| Oracle Database | Database |
| HTML5 | Structure |
| CSS3 | Styling |
| Bootstrap 5 | Responsive UI |
| JavaScript | Client-side logic |
| Apache Tomcat | Web server |
| Eclipse IDE | Development IDE |

---

## 📂 Project Structure

```
LEAVE
│
├── src
│   ├── bean
│   ├── dao
│   ├── servlet
│   ├── util
│   └── filter
│
├── WebContent
│   ├── css
│   ├── images
│   ├── js
│   ├── employee
│   ├── manager
│   ├── admin
│   └── WEB-INF
│
├── database
│
└── README.md
```

---

## 📑 Documentation

| Resource | Description | Link |
|----------|-------------|------|
| 📘 Software Requirement Specification (SRS) | Functional & non-functional requirements | **[View PDF](https://drive.google.com/file/d/1xqE9oSlEFAA3MnhIIrkVxFUUGN-Oqyc7/view?usp=drive_link)** |
| 📙 Software Design Description (SDD) | System design description | **[View PDF](https://drive.google.com/file/d/1ApZ927tb2RnOj0kYMU_SCRNmsQktkD0Y/view?usp=drive_link)** |
| 📗 Software Test Design (STD) | Software test design | **[View PDF](https://drive.google.com/file/d/1OFqwQRk1O6AGjaQa_nTEsHMe6TUfwSLi/view?usp=drive_link)** |
| 📕 Software Test Report (STR) | Software test report | **[View PDF](https://drive.google.com/file/d/1wHrNINfro0JBKtYFWDgW3dOY2jnVWbXm/view?usp=sharing)** |
| 📄 User Manual | Complete user guide | **[View PDF](https://drive.google.com/file/d/1lVjmqhWuc2JreRpWRwBIUhDG3Gb_Rm8_/view?usp=sharing)** |
| 🗄 Oracle Database Report | Oracle database design | **[View PDF](https://drive.google.com/file/d/1LzMBbbjKcUzeNFpzGpsmeJFD3-hgmPfp/view?usp=sharing)** |
| 🎨 Human Computer Interaction (HCI) Report | UI/UX & interface design | **[View PDF](https://drive.google.com/file/d/1mCJu92yrDSqp_458_3hWbcKUj-Q4EQLU/view?usp=sharing)** |
| 📊 Entity Relationship Diagram (ERD) | Database relationship diagram | **Coming Soon** |

---

## 🧪 Testing

The project has been tested for:

- Login authentication
- Leave application
- Leave approval
- Leave rejection
- Leave cancellation
- Leave editing
- Leave balance calculation
- Employee registration
- Employee status
- Holiday management
- Attachment upload
- Leave history
- Profile management
- Change password

---

## 🔄 Workflow

```text
Employee
   │
   ▼
Submit Leave
   │
   ▼
Manager Review
   │
   ▼
Approve / Reject
   │
   ▼
Administrator Monitoring
   │
   ▼
Leave Balance Updated
   │
   ▼
Leave History
```

---

## ⚙ Installation

### 1. Clone Repository

```bash
git clone https://github.com/USERNAME/EmployeeLeave.git
```

### 2. Import into Eclipse

```
File
→ Import
→ Existing Maven Project (or Dynamic Web Project)
```

### 3. Configure Database

Create the database:

```
employee_leave
```

Import the SQL file, then update the connection settings in:

```
DatabaseConnection.java
```

```java
URL
USERNAME
PASSWORD
```

### 4. Deploy

Deploy using:

```
Apache Tomcat 9+
```

### 5. Run

```
http://localhost:8080/LEAVE
```

---

## 📌 Main Modules

- Authentication
- Employee management
- Leave management
- Leave balance management
- Holiday management
- Leave history
- Attachment management
- User profile
- Password management

---

## 🔮 Future Enhancements

- Email notifications
- Mobile responsive design
- Role-based access control
- HR dashboard analytics
- Calendar view
- Multi-level approval workflow
- Annual leave auto-credit
- Export reports (PDF / Excel)
- REST API integration
- Dark mode

---

## 🗄 Database

The system uses Oracle Database to store application data.

Main tables include:

- Employee
- Manager
- Administrator
- Leave
- Leave Type
- Leave Balance
- Holiday
- Attachment

The project follows relational database design principles with normalization and foreign key constraints.

---

## 🏗 Design Pattern

The project follows the **MVC (Model–View–Controller)** architecture:

| Layer | Technology |
|-------|------------|
| View | JSP, HTML, CSS, Bootstrap |
| Controller | Java Servlets |
| Model | JavaBeans |
| Data Access | DAO Classes |
| Database | Oracle Database |

---

## 👨‍💻 Developed By

**Muhammad Ammar Syaathir Bin Abd Rahim**

Bachelor of Information Systems (Hons.) Information Systems Engineering
Universiti Teknologi MARA (UiTM)

---

## 📄 License

This project was developed for **academic and educational purposes**.
Commercial use is not permitted without permission.

---

<div align="center">

⭐ If you found this project useful, consider giving it a star!

</div>
