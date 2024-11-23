# Dental Management System

## Overview

The **Dental Management System** is a comprehensive web application designed to help dental clinics manage patient information, appointments, treatments, and other clinic operations. The system allows staff to easily track patient details, manage appointments, and maintain treatment histories.

## Features

- **Patient Management**: Add, update, and view patient information including personal details, medical history, and contact information.
- **Appointment Scheduling**: Schedule and manage patient appointments, including viewing available time slots.
- **Treatment Records**: Record and track treatments, including diagnosis, procedures, and prescriptions.
- **Billing System**: Generate bills for treatments, manage payments, and track outstanding invoices.
- **User Management**: Admin and staff roles with specific permissions, including creating and managing accounts, and viewing restricted data.
- **Responsive Interface**: Fully responsive design to ensure the system works well on both desktops and mobile devices.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript (for the user interface)
- **Backend**: PHP (for server-side operations)
- **Database**: MySQL (for storing patient, appointment, and treatment data)
- **Authentication**: Secure login system for both admin and staff users

## Installation

### Prerequisites

- **XAMPP** or a similar local server setup
- **MySQL database**

### Steps to Set Up

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/dental-management-system.git
Place the Project in the XAMPP Directory: Move the cloned project folder to the htdocs directory of your XAMPP installation.

Create the Database:

Open phpMyAdmin or MySQL Workbench and create a new database:
sql
Copy code
CREATE DATABASE dental_db;
Import the Database:

Import the database structure and sample data into the dental_db database.
Configure Database Connection:

Edit the config.php file in the root directory to include your database connection details:
php
Copy code
define('DB_SERVER', 'localhost');
define('DB_USERNAME', 'root');
define('DB_PASSWORD', '');
define('DB_DATABASE', 'dental_db');
Start the XAMPP Server:

Start Apache and MySQL from the XAMPP control panel.
Access the Application:

Open your browser and go to http://localhost/dental-management-system/ to access the application.
Usage
Admin Login:
Username: admin
Password: adminpassword
As the admin, you can manage patients, appointments, and other clinic operations.
Staff Login:
Username: staff
Password: staffpassword
Staff members can view and update patient appointments and treatment records.
Contributing
Fork the repository.
Create a new branch for your feature or bug fix.
Make your changes and commit them with descriptive messages.
Push your changes and submit a pull request.
License
This project is licensed under the MIT License - see the LICENSE file for details.

Connect with Me
Facebook
Instagram
sql
Copy code

Now, your Facebook and Instagram links are included in the **Connect with Me** section at the end of the README file!










