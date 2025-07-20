Hospital Management System - Java & MySQL
Project Overview
A comprehensive Hospital Management System developed using:

Frontend: Java Swing (Desktop) + JSP/Servlets (Web)

Backend: MySQL Database

Architecture: MVC with DAO pattern

This system streamlines hospital operations by managing patient records, staff information, appointments, billing, and inventory.

🌟 Key Features
Patient Management
Registration and profile creation

Medical history tracking

Admission/discharge management

Search functionality

Staff Management
Doctor/nurse profiles

Role-based access control

Attendance tracking

Staff scheduling

Appointment System
Online booking

Doctor availability calendar

Visit history

Appointment reminders

Billing & Payments
Automated billing with total calculation

Insurance claim processing

Payment tracking

Financial reports

Inventory Management
Medicine stock control

Medical equipment tracking

Purchase orders

Expiry alerts

Security Features
Secure login system

Password reset via email (JavaMail API)

Token-based authentication (30-minute validity)

🛠️ Technologies Used
Core: Java 8+

Database: MySQL 5.7+ with JDBC

Web: JSP, Servlets

Server: Apache Tomcat 9

UI: Java Swing (Desktop), JSP (Web)

Additional: JavaMail API

📂 Project Structure
text
HospitalManagementSystem/
├── Desktop/                    # Java Swing application
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   │   ├── controllers/
│   │   │   │   ├── dao/
│   │   │   │   ├── model/
│   │   │   │   └── util/
│   │   │   └── resources/
│   │   └── test/
│   └── lib/
│
├── Web/                        # JSP/Servlet application
│   ├── src/main/java/com/company/
│   │   ├── Servlet/           # Controllers
│   │   ├── dao/               # Data Access Objects
│   │   ├── model/             # Business Objects
│   │   └── util/              # Utilities
│   ├── src/main/webapp/
│   │   ├── WEB-INF/
│   │   ├── *.jsp              # View files
│   │   └── resources/
│   └── Servers/               # Tomcat configs
│
└── database/                  # SQL scripts
🚀 Installation Guide
Prerequisites
Java Development Kit (JDK) 8+

MySQL Server 5.7+

For Web: Apache Tomcat 9

MySQL Connector/J

JavaMail API (for email features)

Setup Instructions
Clone the repository:

bash
git clone https://github.com/kumarmaruthi/Hospital-Management-System-Java-Mysql.git
Database Setup:

Create database: hospital_management (Desktop) or hospital_db (Web)

Execute provided SQL scripts

Desktop Application:

Import into Java IDE

Update DBConnection.java with your credentials

Build and run

Web Application:

Import as Maven/Dynamic Web Project

Configure Tomcat server

Update DBUtil.java with your DB credentials

Configure JavaMail in email utilities

Deploy to Tomcat

Access Applications:

Desktop: Run main class

Web: http://localhost:8080/HospitalManagementSystem/Login.jsp

📸 Screenshots
[Include screenshots of both desktop and web interfaces]

🤝 Contributing
Contributions are welcome! Please:

Fork the repository

Create your feature branch

Commit your changes

Push to the branch

Open a pull request

📄 License
MIT License - See LICENSE file for details.

✉️ Contact
For support or questions, please open an issue on GitHub or contact the maintainers.  kumarmaruthi.ind@gmail.com
