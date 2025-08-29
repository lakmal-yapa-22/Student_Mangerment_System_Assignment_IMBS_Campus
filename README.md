# 🌟 Student Management System

A simple yet powerful web-based solution designed for managing student information seamlessly! This project demonstrates essential web development skills including database management, server-side scripting, and front-end design.

**Developed as part of the Web Application Development Project for the Diploma in Information and Communication Technology**

## 🎯 Purpose

This system is built to demonstrate essential web development skills, including:
- Database management and design
- Server-side scripting with PHP
- Front-end development with HTML and CSS
- Full-stack web application development

The project uses PHP, HTML, and CSS alongside the WAMP server environment, making it both functional and easy to maintain.

## 🚀 Features

- **📝 Student Registration**: Quickly add new students to the system with comprehensive details
- **✏️ Update Student Details**: Modify student information such as name, age, or contact details using the student's NIC as the key identifier
- **🗑️ Delete Student Records**: Remove outdated or unwanted student records with simple confirmation
- **🔍 Search Functionality**: Search for students by their NIC or other details for efficient record management
- **📊 View All Students**: Browse through all registered students in an organized interface

## 💻 Technologies Used

| Technology | Purpose |
|------------|---------|
| **PHP** | Backend development, server-side logic, and database communication |
| **HTML** | Structure and markup for web pages |
| **CSS** | Styling and responsive design |
| **MySQL** | Database management for storing student records |
| **WAMP Server** | Local development environment (Windows, Apache, MySQL, PHP) |

## 🛠️ Installation Guide

### Prerequisites
- WAMP Server installed on your system
- Basic knowledge of PHP and MySQL

### Step-by-Step Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/student-management-system.git
   ```

2. **Set Up WAMP Server**
   - Ensure WAMP is installed and running
   - Move the project folder to your WAMP server directory:
     ```
     C:/wamp64/www/student-management-system/
     ```

3. **Database Setup**
   - Start WAMP server (ensure all services are green)
   - Open your browser and navigate to `http://localhost/phpmyadmin`
   - Create a new database named `student_management`
   - Import the SQL file located in the `database/` folder of the project

4. **Configure Database Connection**
   - Open the `config.php` file in your project directory
   - Update the database credentials:
   ```php
   define('DB_SERVER', 'localhost');
   define('DB_USERNAME', 'root');
   define('DB_PASSWORD', '');
   define('DB_NAME', 'student_management');
   ```

5. **Launch the Application**
   - Open your web browser
   - Navigate to: `http://localhost/student-management-system/`
   - You should see the home page of the Student Management System

## 🎮 How to Use the System

### ➕ Adding a Student
1. Navigate to the **Add Student** page
2. Fill out the form with the student's details:
   - Full Name
   - Age
   - National Identity Card (NIC) number
   - Contact information
   - Other relevant details
3. Click **Submit** to register the new student

### ✏️ Updating Student Information
1. Go to the **Update Student** page
2. Enter the NIC of the student you want to update
3. The system will display the current information
4. Make the necessary changes to any field
5. Click **Update** to save the modified information

### 🗑️ Deleting a Student Record
1. Navigate to the **Delete Student** page
2. Enter the NIC of the student you want to remove
3. Review the student information displayed
4. Confirm the deletion when prompted
5. The student record will be permanently removed from the system

### 🔍 Searching for Students
1. Use the search functionality on any page
2. Enter the student's NIC or name
3. View the search results
4. Select the desired student record for viewing or editing

## 📁 Project Structure

```
student-management-system/
├── index.php              # Home page
├── add_student.php        # Add new student form
├── update_student.php     # Update student details
├── delete_student.php     # Delete student records
├── search_student.php     # Search functionality
├── config.php             # Database configuration
├── css/
│   └── style.css         # Styling for the application
├── database/
│   └── student_management.sql  # Database schema
└── README.md             # Project documentation
```

## 🔧 Database Schema

The system uses a MySQL database with the following main table:

**students**
- `id` (Primary Key, Auto Increment)
- `nic` (Unique, VARCHAR)
- `full_name` (VARCHAR)
- `age` (INT)
- `email` (VARCHAR)
- `phone` (VARCHAR)
- `address` (TEXT)
- `created_at` (TIMESTAMP)
- `updated_at` (TIMESTAMP)

## 🎨 Future Enhancements

- [ ] **Advanced Search Filters**: Filter by age range, email domain, etc.
- [ ] **Student Profile Photos**: Upload and display student images
- [ ] **Enhanced Security**: Input validation, SQL injection prevention
- [ ] **User Authentication**: Login system for administrators
- [ ] **Export Functionality**: Export student data to PDF or Excel
- [ ] **Responsive Design**: Mobile-friendly interface improvements
- [ ] **Backup System**: Automated database backups

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/AmazingFeature`)
3. **Commit** your changes (`git commit -m 'Add some AmazingFeature'`)
4. **Push** to the branch (`git push origin feature/AmazingFeature`)
5. **Open** a Pull Request

### Areas for Contribution
- Bug fixes and improvements
- UI/UX enhancements
- Security improvements
- Documentation updates
- New feature implementations

## 🐛 Known Issues

- Form validation could be enhanced for better user experience
- Error handling needs improvement for edge cases
- Mobile responsiveness requires optimization

## 📝 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

## 📞 Support

If you encounter any issues or have questions about the project:
- Open an issue on GitHub
- Check the documentation for common problems
- Review the code comments for implementation details

## 🏆 Acknowledgments

- **Course**: Web Application Development
- **Program**: Diploma in Information and Communication Technology
- **Technologies**: Thanks to the PHP community and WAMP development team

---

**⭐ If you found this project helpful, please give it a star!**

> Built with ❤️ for learning and educational purposes
