# Hostel Management System -

## More Details / Buy This Project

For full source code, documentation, and support, visit: [updategadh.com](https://updategadh.com/hostel-management-system-php-and-mysql/)

## Overview
The Hostel Management System is a role-based web application designed for colleges and educational institutions to manage hostel registration, room allocation, complaint handling, and internal communication between students, hostel managers, and administrators.

## Screenshot
<img width="1870" height="525" alt="image" src="https://github.com/user-attachments/assets/07ff73d8-e261-476d-8972-e823471b786c" />
<img width="1904" height="566" alt="image" src="https://github.com/user-attachments/assets/735786c7-f67f-4175-87a6-8b7129f5cc4d" />


## Project Objective
The main goal of the system is to simplify hostel operations by providing a centralized platform where:
- students can register and apply for hostel accommodation,
- managers can review applications and assign rooms,
- administrators can oversee the entire hostel workflow,
- complaints and messages can be handled in a structured manner.

## Key Features
- User registration and role-based login
- Student hostel application workflow
- Room allocation and vacancy management
- Complaint submission and status tracking
- Internal messaging between students and managers
- Admin control over hostels, managers, students, and applications

## User Roles
- Admin: manages hostels, rooms, users, applications, and complaints
- Hostel Manager: reviews applications, allocates rooms, processes complaints, and vacates rooms
- Student: registers, applies for hostel, tracks room status, submits complaints, and communicates with the manager

## Technology Stack
- PHP (procedural style with MySQLi)
- MySQL database
- HTML, CSS, JavaScript
- Apache/PHP environment such as XAMPP, WAMP, or LAMP

## Installation and Setup
1. Place the project folder inside your web server directory, for example C:\xampp\htdocs\Hostel.
2. Start Apache and MySQL.
3. Open http://localhost/Hostel/install.php in your browser.
4. The installer will create the database schema and seed demo accounts.
5. After setup, delete install.php for security.
6. Open http://localhost/Hostel/ to access the system.

## Demo Accounts
- Admin: admin@hostel.com / Admin@123
- Manager: manager@hostel.com / Manager@123
- Student: student@hostel.com / Student@123

## System Workflow
1. Student registers and logs in.
2. Student submits a hostel application.
3. Manager reviews the application and assigns an available room.
4. Student can raise complaints and track their progress.
5. Manager and student can exchange messages through the built-in messaging system.
6. When a student vacates, the room becomes available again.

## Project Structure
- config/: database configuration and app constants
- includes/: shared authentication, layout, and helper functions
- auth/: login, registration, and logout pages
- admin/: admin-only management pages
- manager/: manager-only operational pages
- student/: student-facing pages
- messages/: internal messaging module
- assets/: CSS and JavaScript assets
- sql/: SQL schema for the database

## Notes
The application is lightweight and suitable for small to medium college hostel operations. It is built without a framework, making it easy to understand and modify for academic or practical use.

## Future Improvements
- Add email notifications
- Improve reporting and analytics
- Add room booking history and audit logs
- Enhance UI with a modern frontend framework

