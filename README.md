
# 📄 Project Description

The **Bank Account Management System** is a web-based application developed using **Java Servlets,HTML, and CSS**. The project allows users to perform basic banking operations such as adding a new account, viewing account details, updating account information, and deleting accounts from the system.

The application uses **Java Servlets** to handle client requests and process business logic, while **Hibernate ORM** is used to manage database operations and simplify interaction with the database. HTML forms are used to collect user input, and CSS is used to design the user interface.

Each operation is handled by a dedicated servlet such as **AddAccountServlet, DeleteAccountServlet, UpdateAccountServlet, and ViewAccountServlet**, making the application modular and easy to maintain.

This project demonstrates the implementation of **CRUD operations, servlet-based web development, database connectivity, and transaction management using Hibernate**. It helps in understanding the architecture of Java web applications and how backend technologies interact with frontend interfaces.

# 🏦 Bank Account Management System (Java Servlet + Hibernate)

## 📌 Project Overview
The Bank Account Management System is a web-based application developed using Java Servlets and Hibernate ORM. The system allows users to manage bank account records by performing operations such as adding new accounts, viewing account details, updating account information, and deleting accounts.

The application demonstrates the use of Java web technologies along with Hibernate for efficient database interaction and transaction management.

---

## 🚀 Features

- Add new bank account
- View account details
- Update account information
- Delete account records
- Logout functionality
- Database operations using Hibernate ORM
- Simple and user-friendly interface

---

## 🛠 Technologies Used

### Backend
- Java
- Java Servlets
- Hibernate ORM

### Frontend
- HTML
- CSS

### Server
- Apache Tomcat

### Tools
- Eclipse IDE

---

## 📁 Project Structure

```
ProjectonServlet
│
├── src/main/java/bank
│   ├── AddAccountServlet.java
│   ├── DeleteAccountServlet.java
│   ├── UpdateAccountServlet.java
│   ├── ViewAccountServlet.java
│   └── LogoutServlet.java
│
├── src/main/webapp
│   ├── index.html
│   ├── add.html
│   ├── delete.html
│   ├── update.html
│   ├── view.html
│   └── style.css
│
└── hibernate.cfg.xml
```

---

## ⚙️ How It Works

1. User enters account details through HTML forms.
2. The request is sent to a corresponding Servlet.
3. The Servlet processes the request.
4. Hibernate ORM handles database operations.
5. The result is displayed to the user.

---

## ▶️ How to Run the Project

### Step 1: Install Requirements
- Java JDK
- Eclipse IDE
- Apache Tomcat Server
- MySQL / Oracle Database

### Step 2: Import Project
Import the project into Eclipse as a **Dynamic Web Project**.

### Step 3: Configure Database
Update the database connection in:

```
hibernate.cfg.xml
```

### Step 4: Deploy Project
Run the project on **Apache Tomcat Server**.

### Step 5: Open in Browser

```
http://localhost:8080/ProjectonServlet
```

---

## 💡 Learning Outcomes

- Java Servlet development
- CRUD operations in web applications
- Hibernate ORM integration
- Database transaction management
- Building Java web applications using MVC structure

---

## 👩‍💻 Author

**Shirisha Vangala**

