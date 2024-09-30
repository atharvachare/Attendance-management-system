Student Attendance Management System
Overview
This Student Attendance Management System is a simple web-based application designed to manage student attendance efficiently. Built using PHP and MySQL, the system allows teachers or administrators to keep track of student attendance records, view attendance summaries, and generate reports.

Features
Student Registration: Register students into the system with essential details like name, roll number, and class.
Mark Attendance: Easily mark students' attendance for each class or day.
Attendance Reports: Generate daily, weekly, or monthly attendance reports.
Admin Panel: Secure admin access to manage students, view overall attendance, and generate detailed reports.
Responsive Design: Accessible on both desktop and mobile platforms.

Tech Stack
Frontend: HTML, CSS, JavaScript
Backend: PHP
Database: MySQL (via phpMyAdmin in XAMPP)
Web Server: Apache (via XAMPP)

Prerequisites
XAMPP (Apache, MySQL, PHP)
Make sure XAMPP is installed and running on your machine.

Installation
1.Clone the repository
2.Move the project to XAMPP's htdocs folder:
Copy the cloned project folder and paste it into the htdocs directory in your XAMPP installation folder. For example:C:\xampp\htdocs\attendance-management-system
3.Start XAMPP:
  Open XAMPP Control Panel.
  Start both Apache and MySQL modules.
4.Set up the database:
  Open your browser and go to http://localhost/phpmyadmin/.
  Create a new database named simple_attendance_db.
  Import the simple_attendance_db file in db folder:
  Click on the newly created database.
  Go to the Import tab and select the simple_attendance_db file located in the project folder.
  Click Go to import the database structure and sample data.
5.Run the project:  Open your browser and navigate to http://localhost/attendance-management-system/ to view the application.
