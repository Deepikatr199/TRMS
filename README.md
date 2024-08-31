# Teachers Record Management System (TRMS) - Setup Guide
This guide will help you set up and run the Teachers Record Management System (TRMS) project on your local machine.

1. Download the Project Files
Download the project zip file from the provided source.
Extract the zip file.

2. Set Up the Project Directory
Copy the trms folder from the extracted files.
Paste the trms folder inside your web server's root directory:
XAMPP: xampp/htdocs
WAMP: wamp/www
LAMP: var/www/html

3. Set Up the Database
Open PHPMyAdmin in your browser.
Create a new database with the name trms.
Import the trms.sql file located in the SQL file folder inside the extracted package:
Click on the Import tab in PHPMyAdmin.
Choose the trms.sql file and click Go.

4. Run the Project
Open your browser and navigate to: http://localhost/TRMS-PHP-Project/trms/
This will open the frontend of the TRMS application.

Credentials
You can log in using the following credentials:

Admin Panel:

Username: admin
Password: Test@123
Teacher Panel:

Username: jogoe12@yourdomain.com
Password: Test@123
OR Register a new Teacher account.
Note:
If you encounter any issues while setting up, make sure that your web server (XAMPP, WAMP, or LAMP) is running and the database is correctly configured.

