Healthcare Management System - 
The Healthcare Management System is a Java-based application designed to assist healthcare professionals in managing patient records, appointments, and medical services efficiently.

Features
Patient Management: Add, update, and view patient records including personal details, medical history, and appointments.
Appointment Scheduling: Schedule appointments for patients with doctors and manage appointment calendars.
Medical Services: Manage and track medical services provided to patients, including prescriptions, treatments, and tests.
User Authentication: Secure login system for healthcare professionals with role-based access control.
Technologies Used
Java
JavaFX for the user interface
MySQL for database management
JDBC for database connectivity
Maven for project management and dependency resolution
Setup Instructions
Clone the Repository:

bash
Copy code
git clone https://github.com/yourusername/healthcare-management.git
Database Setup:

Install MySQL and create a new database named healthcare_management.
Import the database schema from the database.sql file located in the database directory.
IDE Configuration:

Import the project into your preferred Java IDE (e.g., IntelliJ IDEA, Eclipse).
Set up the MySQL JDBC driver in your IDE.
Run the Application:

Build the project using Maven.
Run the Main class located in the src/main/java directory.
Usage
Login:

Use the provided username and password to log in to the system.
Dashboard:

Navigate through different modules using the sidebar menu.
Manage patients, appointments, and medical services as per your role.
Patient Management:

Add new patients, update existing records, and view patient details.
Schedule appointments for patients with doctors.
Appointment Management:

View upcoming appointments and manage appointment calendars.
Reschedule or cancel appointments as necessary.
Medical Services:

Record medical services provided to patients, including prescriptions, treatments, and tests.
View and update service records.
