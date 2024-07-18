# Clinic Management System

The Clinic Management System (CMS) is designed to digitize and streamline clinic operations, replacing manual processes with a comprehensive web application. Built with PHP and MySQL, this system focuses on automating internal workflows and managing various aspects of small to medium-sized medical clinics, enhancing efficiency and data retrieval.

# Key Features
- Patient Registration: Simplifies the process of registering new patients.
- Health Record Management: Maintains a detailed history of patient health records.
- Laboratory Management: Organizes and manages laboratory tests and results.
- Pharmacy Management: Oversees the dispensing and inventory of medications.
- X-Ray Management: Manages X-ray imaging and records.

# Installation Guide
1. Create the Database: Set up a new database for the application.
2. Import Database File: Import the SQL file located in the 'sql' directory into your database.
3. Configure Database Settings: Update the database configuration in 'application/configs/database.php' to match your   database credentials.
4. Access the Web Application: Open your web browser and navigate to the application.
5. User Account Signup: To create a user account, navigate to the signup page at 'http://<hostname>[
]/[subdirectory/][index.php/]account/signup'. Ensure the first user registered has an admin role.

# Signup Page Examples
- http://localhost:8080/clinic-management-system/index.php/account/signup
- http://localhost/account/signup


By following these steps, you can easily set up and start using the Clinic Management System to improve the operational efficiency of your clinic.