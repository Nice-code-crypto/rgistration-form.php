# Student Registration System

A robust, secure, and mobile-responsive student registration web application built with **HTML5**, **CSS3**, **PHP**, and **MySQL/MariaDB**, designed to capture student details, validate input data, and store records securely in a relational database.



## Features

* **Responsive User Interface:** Clean, modern, and mobile-friendly form design.
* **Server-Side Validation:** Comprehensive PHP backend validation checking for required fields, email formatting, phone number patterns, matriculation number format, valid dates of birth, and matching passwords.
* **Secure Database Insertion:** Uses **PHP Data Objects (PDO)** with parameterized queries to protect against SQL injection.
* **Password Security:** Hashes user passwords securely using PHP's native `password_hash()` function (never stores plain text passwords).
* **Input Preservation:** Preserves previously entered user input if validation fails so users do not have to retype everything.
* **Duplicate Prevention:** Validates uniqueness constraints on emails and matriculation numbers.



## Tech Stack

* **Frontend:** HTML5, CSS3
* **Backend:** PHP (Session management, filter validation, PDO)
* **Database:** MySQL / MariaDB (via XAMPP or local server)



## Project Structure


Registration-form/
│
├── index.php         # Student registration form UI & client-facing view
├── register.php      # Server-side processing, validation, and database insertion
└── README.md         # Project documentation
BY Nice-code-crypto
