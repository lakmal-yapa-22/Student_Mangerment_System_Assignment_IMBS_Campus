🌟 Student Management System - Web Application Development Project 🌟
Welcome to the Student Management System, a simple yet powerful web-based solution designed for managing student information seamlessly! Developed as part of the Web Application Development Project for the Diploma in Information and Communication Technology, this project allows users to add, update, and delete student records with ease.

🎯 Purpose
The system is built to demonstrate essential web development skills, such as database management, server-side scripting, and front-end design. Using PHP, HTML, and CSS alongside the WAMP server, this project is both functional and easy to maintain.

🚀 Features
📝 Student Registration: Quickly add new students to the system.
✏️ Update Student Details: Modify student information, like name, age, or contact details, using the student's NIC as the key identifier.
🗑️ Delete Student Records: Remove outdated or unwanted student records with a simple click.
🔍 Search Functionality: Search for students by their NIC or other details for easy record management.
💻 Technologies
PHP: Powers the backend, handling data management and communication with the database.
HTML & CSS: For creating a user-friendly, responsive interface.
WAMP Server: Provides the local environment for hosting the project and managing the MySQL database.
🛠️ Installation Guide
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/student-management-system.git
Set up WAMP:

Move the project to your WAMP server directory (e.g., C:/wamp64/www/student-management-system).
Database Setup:

Start WAMP and open phpMyAdmin.
Create a new database called student_management.
Import the SQL file located in the database/ folder.
Configure Database Connection:

Open config.php and update the database credentials:
php
Copy code
define('DB_SERVER', 'localhost');
define('DB_USERNAME', 'root');
define('DB_PASSWORD', '');
define('DB_NAME', 'student_management');
Launch the App:

Open your browser and go to:
perl
Copy code
http://localhost/student-management-system/
🎮 How to Use the System
➕ Add a Student
Navigate to the Add Student page.
Fill out the form with the student’s details (name, age, NIC, etc.).
Submit the form to register the new student.
✏️ Update a Student
Head to the Update Student page.
Enter the NIC of the student you want to update.
Make the necessary changes and click Update to save the updated information.
🗑️ Delete a Student
Go to the Delete Student page.
Enter the NIC of the student you want to remove from the system.
Confirm the deletion, and the student will be permanently deleted.
🎨 Future Plans
Adding more advanced search filters.
Implementing student profile photos.
Enhanced security features.
🙌 Contributions
Feel free to contribute to this project by submitting issues or opening a pull request. Any improvements or bug fixes are always welcome!

📄 License
This project is licensed under the MIT License.
