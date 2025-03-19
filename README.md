🏥 Hospital Management System (Java + MySQL)
📌 Project Description
This Hospital Management System is a Java-based application that uses JDBC to perform CRUD operations on a MySQL database. It helps manage:

Patients
Staff
Departments
Appointments
The project is menu-driven and allows users to interact with the system through the console.

⚙️ Features
✅ Add, view, update, and delete patient records
✅ Add, view, update, and delete staff records with department allocation
✅ Manage departments (add and delete)
✅ Schedule and update appointments between patients and staff
✅ View all appointments with patient and staff details

💻 Technologies Used
Java
JDBC (Java Database Connectivity)
MySQL Database
Console-based User Interface
🗃️ Database Schema Overview
Tables:
patient (patient_id, patient_name, address, phone_no, gender, dob)
staff (staff_id, staff_name, address, phone_no, gender, dob, department_name, department_id)
department (department_no, department_name)
appointment (appointment_id, patient_name, staff_name, appoinment_date_and_time, appoinment_status)
🚀 How to Run the Project
Clone or Download the project
Set up the MySQL Database:
Create the database and tables based on the schema mentioned above.
Configure Database Connection:
Update Connectionclass.getconnection() with your MySQL URL, username, and password.
Compile the Java Program:
bash
Copy
Edit
javac Hosptialmanagement.java
Run the Program:
bash
Copy
Edit
java Hosptialmanagement
Follow the console menu to perform operations.
📖 Sample Menu
Copy
Edit
1) Patient
2) Staff
3) Appointment
4) Department
Each option allows you to perform actions like create, update, delete, or fetch data.

✅ Future Improvements
Add GUI (Java Swing / JavaFX)
Integrate authentication system for staff
Generate PDF reports for appointments
Handle input validation more robustly
Separate service and database layers for better code structure
🙌 Author
Reymonselvakumar G M
B.Tech Student | Java Developer
