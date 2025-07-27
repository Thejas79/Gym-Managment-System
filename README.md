# Gym-Managment-System
website to manage gym data by using PHP , MYSQL, HTML, javascript
This is a simple Gym Management System developed using PHP, MySQL, HTML, and CSS. It allows gym owners to manage members, plans, trainers, and more from a web-based interface.

📁 Project Contents
The project zip includes the following main folders/files:

index.php – The landing (login) page.

dashboard.php – Admin dashboard for managing system operations.

includes/ – Contains database connection and reusable PHP components.

classes/ – Contains logic like class files for user handling.

assets/ – CSS, JS, and images used in the UI.

sql/gymdb.sql – SQL file to set up the database.

members.php, plans.php, trainers.php, etc. – Modules to manage each category.

logout.php – Logout script.

🛠️ Requirements
XAMPP / WAMP / LAMP (or any local server stack with Apache, PHP, MySQL)

PHP 7.x or higher

MySQL database

🚀 How to Run the Project
Download and Extract

Unzip the file: GYM-Management-System-using-PHP.zip

Place it in the htdocs folder (if using XAMPP).

Import Database

Open phpMyAdmin

Create a new database, e.g., gymdb

Click Import > Choose the file: sql/gymdb.sql > Click Go

Update Database Config

Open the file: includes/config.php or similar (where DB connection is defined)

Ensure your DB username/password/database name matches your local setup.

Run the Application

Open your browser and go to:
http://localhost/GYM-Management-System-using-PHP

Login

Use the default admin credentials (check the database users table for username/password or hardcoded values in login.php).

🔒 Features
Member Registration and Management

Trainer Management

Workout and Plan Management

Payment Handling

Admin Dashboard

Login/Logout System



🙏 Credits
Developed using PHP and MySQL. Front-end styled using HTML/CSS.
