# Apartment Visitors Management System (AVMS)

## 📌 Project Overview

The Apartment Visitors Management System (AVMS) is a web-based application developed to manage visitor records in residential apartments efficiently. The system enables administrators to register visitors, issue visitor passes, monitor visitor entries and exits, and generate reports for security and management purposes.

This project helps apartment management improve security, maintain visitor records digitally, and reduce manual paperwork.

---

## 🚀 Features

### Admin Module
- Secure Admin Login
- Dashboard with Visitor Statistics
- Add Visitor Categories
- Register New Visitors
- Generate Visitor Passes
- Manage Visitor Records
- Search Visitor Details
- Generate Reports by Date Range
- Update Visitor Information
- Change Password
- Manage Admin Profile

### Visitor Management
- Record Visitor Details
- Track Entry and Exit Times
- Store Contact Information
- Visitor Pass Generation
- Visitor History Management

### Reporting
- Visitor Reports
- Pass Reports
- Date-wise Reports
- Search Functionality

---

## 🛠️ Technology Stack

### Frontend
- HTML5
- CSS3
- Bootstrap
- JavaScript
- jQuery

### Backend
- PHP

### Database
- MySQL

### Server
- XAMPP / WAMP / LAMP

---

## 📂 Project Structure

```
AVMS/
│
├── admin-profile.php
├── dashboard.php
├── create-pass.php
├── category.php
├── search-visitor.php
├── bwdates-reports.php
├── bwdates-passreports.php
├── includes/
├── css/
├── images/
├── js/
└── SQL File/
    └── avmsdb.sql
```

---

## ⚙️ Installation Guide

### Prerequisites

- PHP 7.x or above
- MySQL
- XAMPP/WAMP/LAMP Server

### Steps to Run the Project

#### 1. Clone the Repository

```bash
git clone https://github.com/your-username/AVMS.git
```

#### 2. Move Project Folder

Copy the project folder into:

- XAMPP: `xampp/htdocs`
- WAMP: `wamp/www`
- LAMP: `/var/www/html`

#### 3. Create Database

Open:

```
http://localhost/phpmyadmin
```

Create a database named:

```sql
avmsdb
```

#### 4. Import Database

Import the SQL file:

```
SQL File/avmsdb.sql
```

#### 5. Run the Application

Open:

```
http://localhost/avms
```

---

## 🔐 Admin Credentials

| Username | Password |
|-----------|-----------|
| admin | Test@123 |

> Change the default password after first login for security purposes.

---

## 📸 Screenshots

Add screenshots of the following pages:

- Login Page
- Dashboard
- Visitor Registration
- Visitor Pass Creation
- Reports Page

Example:

```markdown
![Dashboard](screenshots/dashboard.png)
```

---

## 🎯 Future Enhancements

- Resident Login Module
- Visitor QR Code Generation
- Email Notifications
- SMS Alerts
- Mobile Responsive Design Improvements
- Visitor Analytics Dashboard
- Face Recognition Integration

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Added new feature"
```

4. Push to your branch

```bash
git push origin feature-name
```

5. Create a Pull Request

---

## 📄 License

This project is developed for educational and academic purposes.

---

## 👨‍💻 Author

**Harika Killi**  
B.Tech CSE (AIML)  
SRM Institute of Science and Technology, Chennai

---

## ⭐ Support

If you found this project useful, please give it a ⭐ on GitHub.
