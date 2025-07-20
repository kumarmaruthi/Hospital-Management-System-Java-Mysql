# Hospital-Management-System-Java-Mysql
Hospital Management System
Hospital Management System - Java, JSP, MySQL

A full-featured Hospital Management System built using Java, JSP, Servlets, and MySQL. This web application helps manage patient records, hospital staff, billing information, and appointment schedules. Designed with a clean interface and robust backend integration, it simplifies day-to-day hospital operations.

🔧 Features

👤 Patient Registration and Login

💊 Doctor/Staff Search

🏥 Billing System with Auto Total Calculation

🔐 Secure Login & Password Reset (via Email)

📄 JSP Frontend + Servlet Backend

🔗 JDBC MySQL Integration

📁 Modular DAO + MVC Architecture

📁 Folder Structure

HospitalManagementSystem/
├── src/main/java/com/company
│   ├── Servlet/                 # JSP/Servlet controllers
│   ├── dao/                    # DAO interfaces and implementations
│   ├── model/                  # POJO classes
│   └── Utilte/DBUtil.java      # DB connection utility
├── src/main/webapp/
│   ├── *.jsp                   # JSP front-end files
│   ├── shekharhospitallogo.png
│   └── WEB-INF/lib/           # JAR dependencies
Servers/
└── Tomcat Configuration Files

⚙️ Tech Stack

Java

JSP & Servlets

JDBC

MySQL

Apache Tomcat 9

JavaMail API

🚀 Getting Started

Clone the repository

git clone https://github.com/kumarmaruthi/Hospital-Management-System-Java-Mysql.git

Import into Eclipse/IDE as an existing Maven or Dynamic Web Project.

Configure Database

Create a database: hospital_db

Import tables from provided SQL script (if included)

Update DB credentials in DBUtil.java

Run on Apache Tomcat v9

Add Servers/ configuration if needed

Access via http://localhost:8080/HospitalManagementSystem/Login.jsp

📧 Password Reset Functionality

Uses JavaMail API and Gmail App Password

Secure token valid for 30 minutes

Works via ResetPasswordServlet and ResetPasswordForm.jsp

📸 Screenshots




🤝 Contributing

Pull requests and suggestions are welcome. For major changes, please open an issue first to discuss what you would like to change.

📄 License

This project is licensed under the MIT License - see the LICENSE file for details.
