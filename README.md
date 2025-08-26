🏥 Hospital Management System – Java & MySQL

A comprehensive Hospital Management System developed using Java and MySQL. The project is designed to streamline hospital operations by managing patients, staff, appointments, billing, and inventory.

⚙️ Tech Stack

Frontend (Desktop): Java Swing

Frontend (Web): JSP, Servlets

Backend: MySQL Database

Architecture: MVC with DAO pattern

Server: Apache Tomcat 9

Additional: JavaMail API (for password reset & notifications)

🌟 Key Features
👨‍⚕️ Patient Management

Registration and profile creation

Medical history tracking

Admission/discharge management

Advanced search functionality

🧑‍💼 Staff Management

Doctor/nurse profiles

Role-based access control

Attendance tracking

Staff scheduling

📅 Appointment System

Online booking with doctor availability calendar

Visit history tracking

Appointment reminders

💳 Billing & Payments

Automated billing with total calculation

Insurance claim processing

Payment tracking

Financial reports

📦 Inventory Management

Medicine stock control

Medical equipment tracking

Purchase order generation

Expiry alerts

🔒 Security Features

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
HospitalManagementSystem/
├── Desktop/              # Java Swing application
│   ├── src/
│   │   ├── main/java/
│   │   │   ├── controllers/
│   │   │   ├── dao/
│   │   │   ├── model/
│   │   │   └── util/
│   │   └── resources/
│   └── lib/
│
├── Web/                  # JSP/Servlet application
│   ├── src/main/java/com/company/
│   │   ├── servlet/      # Controllers
│   │   ├── dao/          # Data Access Objects
│   │   ├── model/        # Business Objects
│   │   └── util/         # Utilities
│   ├── src/main/webapp/
│   │   ├── WEB-INF/
│   │   ├── *.jsp         # View files
│   │   └── resources/
│   └── Servers/          # Tomcat configs
│
└── database/             # SQL scripts

🚀 Installation Guide
✅ Prerequisites

JDK 8+

MySQL Server 5.7+

Apache Tomcat 9

MySQL Connector/J

JavaMail API

📝 Setup Instructions

Clone the repository

git clone https://github.com/kumarmaruthi/Hospital-Management-System-Java-Mysql.git


Database Setup

Create database: hospital_management (Desktop) or hospital_db (Web)

Execute provided SQL scripts

Desktop Application

Import into Java IDE

Update DBConnection.java with your DB credentials

Build and run

Web Application

Import as Maven/Dynamic Web Project

Configure Tomcat server

Update DBUtil.java with your DB credentials

Configure JavaMail in email utilities

Deploy to Tomcat

Access Applications

Desktop: Run main class

Web: http://localhost:8080/HospitalManagementSystem/Login.jsp

📸 Screenshots

(Add screenshots of both desktop and web interfaces here)

🤝 Contributing

Contributions are welcome! Please:

Fork the repository

Create your feature branch (git checkout -b feature/YourFeature)

Commit your changes (git commit -m 'Add new feature')

Push to the branch (git push origin feature/YourFeature)

Open a Pull Request

📄 License

This project is licensed under the MIT License – see the LICENSE
 file for details.

✉️ Contact

For support or questions:
📧 kumarmaruthi.ind@gmail.com
