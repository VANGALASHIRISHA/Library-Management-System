Bank Management System
📌 Project Overview

The Bank Management System is a web-based application developed using Java Servlets, HTML, and JDBC.
The system allows administrators to manage bank accounts efficiently by performing complete CRUD operations with secure session handling and logout functionality.

🚀 Features

✅ Create new bank accounts
✅ View account details
✅ Update customer information
✅ Delete bank accounts
✅ Login & Logout functionality
✅ Real-time database connectivity using JDBC
✅ Dynamic request–response handling using Servlets
✅ User-friendly HTML interface

🛠️ Technologies Used

Frontend:

HTML

CSS

Backend:

Java Servlets

JDBC

Database:

MySQL / Oracle Database

Server:

Apache Tomcat

📂 Project Structure
BankManagementSystem/
│
├── src/main/java/
│   ├── AddAccountServlet.java
│   ├── ViewAccountServlet.java
│   ├── UpdateAccountServlet.java
│   ├── DeleteAccountServlet.java
│   ├── LoginServlet.java
│   └── LogoutServlet.java
│
├── src/main/webapp/
│   ├── index.html
│   ├── login.html
│   ├── addAccount.html
│   ├── updateAccount.html
│   ├── delete.html
│   ├── logout.html
│   └── style.css
⚙️ How It Works

1.User logs in through login.html
2.After successful login → redirected to index.html

3.User can:

Add Account

View Account

Update Account

Delete Account

4.Logout option ends the session securely.

▶️ How to Run

1.Install Database (MySQL / Oracle)

2.Create required table

3.Configure DB connection in Servlets

4.Deploy project on Apache Tomcat

5.Open in browser:

http://localhost:8080/BankManagementSystem
