# 4.Design a Webpage Using a CMS:

Objective: To familiarize the intern with content management systems.
Details: Create a webpage or a small website using a CMS like WordPress. This task should include customizing a theme and adding content.
Tools: WordPress (or another CMS), HTML, CSS, and some basic PHP knowledge for customization.
# class-attendance-system

This code creates a login page for a Student Attendance Management System, allowing users to log in as either an Administrator or a ClassTeacher. Here's a summary of its components and functionality:

- **HTML Structure**: 
  - Contains a form with fields for selecting user role, entering email, and password.
  - Includes a background image and a logo.
  - Utilizes Bootstrap for styling and layout.

- **PHP Logic**: 
  - Connects to the database and starts a session.
  - On form submission, it checks user credentials against the database for the selected role.
  - Redirects users to the appropriate dashboard if login is successful or displays an error message if not.

- **Security Considerations**: 
  - Currently uses MD5 for password hashing (which is insecure); more secure hashing methods like bcrypt are recommended.
  - Vulnerable to SQL injection; using prepared statements is advised for security.

- **JavaScript**: 
  - Includes jQuery and Bootstrap scripts for interactive features and styling.

The page provides a functional but basic login system that requires improvements for better security and robustness.

## login page for class teachers in a Student Attendance Management System.

This code creates a login page for class teachers in a Student Attendance Management System. Here's a concise summary:

- **Purpose**: Provides a login form for class teachers to access their account.
- **Structure**:
  - **HTML**: Includes a form with fields for email and password, styled with Bootstrap. The form also features a logo and a submit button.
  - **PHP**: Handles form submission by checking the credentials against the database. If valid, it sets session variables and redirects the user to the ClassTeacher dashboard; otherwise, it displays an error message.
- **Security Notes**:
  - **Password Hashing**: Uses MD5, which is insecure. A more secure hashing method like bcrypt is recommended.
  - **SQL Injection**: Vulnerable to SQL injection. Prepared statements should be used to enhance security.

The page also includes links for additional actions (e.g., login options) and JavaScript for interactivity.
