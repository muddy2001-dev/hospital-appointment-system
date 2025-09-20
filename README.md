🏥 Online Hospital Scheduling System

An online appointment scheduling system for hospitals built with PHP, AJAX, JavaScript, and MySQL (running on XAMPP).
The system provides dashboards for patients (users), receptionists, and administrators to manage hospital appointments efficiently.

🚀 Features
👨‍⚕️ User (Patient) Dashboard

Register & login

Book, reschedule, or cancel appointments

View appointment history

🧾 Receptionist Dashboard

Confirm patient appointments

View daily/weekly appointments

🛠️ Admin Dashboard

Manage users (patients & receptionists)

View reports & analytics

Oversee system activity

✨ Other Features

🌙 Dark Mode for better accessibility

🌍 Google Translate Integration (English ↔ Swahili)

🔒 Secure login system with demo accounts

📂 Project Structure
C:\xampp\htdocs\app\
│
├── admin.php          # Admin dashboard
├── welcome.php        # User (patient) dashboard
├── rec_dashb.php      # Receptionist dashboard
├── mass.sql           # Database file
├── database.php       # Database connection
├── vendor/            # Required for Google Sign-In
└── README.md          # Documentation

🔑 Demo Accounts
👨‍⚕️ User

Email: user@example.com

Password: User@123

🧾 Receptionist

Email: receptionist@example.com

Password: Rec@123

🛠️ Admin

Email: admin@example.com

Password: Admin@123

🛠️ Installation

Clone or download the project into C:\xampp\htdocs\app\

git clone https://github.com/muddy2001-dev/hospital-appointment-system.git


Start XAMPP (Apache & MySQL).

Import the database:

Open http://localhost/phpmyadmin

Create a database named mass

Import the file mass.sql

Configure the database connection:

Open database.php

Update database username, password, and name (mass)

Install vendor dependencies (for Google Sign-In):

Navigate to project folder:

cd C:\xampp\htdocs\app\


Install required packages:

composer install


Run the project in your browser:

User → http://localhost/app/welcome.php

Receptionist → http://localhost/app/rec_dashb.php

Admin → http://localhost/app/admin.php

⚙️ Technologies Used

Frontend: HTML, CSS, JavaScript, AJAX

Backend: PHP (XAMPP)

Database: MySQL (mass.sql)

Additional Tools: Google Translate API, Dark Mode toggle, Composer (vendor setup for Google Sign-In)

📌 Notes

Some features (like email notifications and Google Sign-In) require a real email configuration and vendor/ dependencies installed.

Make sure Composer is installed on your machine to enable these features.
