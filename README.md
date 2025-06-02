## ✈️ Airline Management System

This is a **web-based Airline Management System** developed using **PHP** and **MySQL**. It provides essential functionalities for flight booking, user registration, ticket management, and payment tracking in a simplified airline reservation environment.

---

### 📁 Project Structure

* `admin/` – Admin panel components (flight, booking, user management)
* `assets/` – CSS, JS, images, and other static files
* `DATABASE FILE/` – Contains SQL database schema (likely `.sql` file)
* `helpers/` – Reusable helper scripts
* `includes/` – PHP include files (headers, configs, DB connection)
* `sub-views/` – Page fragments (modular views)
* `vendor/` – External dependencies (if any)

---

### 🧰 Technologies Used

* **Frontend**: HTML, CSS, JavaScript
* **Backend**: PHP
* **Database**: MySQL
* **Architecture**: Modular PHP with sub-views/includes structure

---

### 🚀 Features

* User Registration and Login
* Flight Booking and E-ticket generation
* View My Flights / Bookings
* Payment simulation and success status tracking
* Password reset functionality
* Feedback system

---

### ⚙️ Setup Instructions

1. **Clone or Download the ZIP**
   Extract the contents and place them in your web server directory (e.g., `htdocs` for XAMPP).

2. **Set Up the Database**

   * Import the `.sql` file from the `DATABASE FILE/` folder into your MySQL server (via phpMyAdmin or CLI).
   * Update the database credentials in `includes/config.php` (or similar DB config file).

3. **Run the Application**
   Open your browser and go to:
   `http://localhost/your-folder-name/index.php`

---

### 🔑 Sample Files

* `index.php` – Home page
* `register.php` – User registration
* `login.php` – Login handler
* `book_flight.php` – Booking form
* `e_ticket.php` – Ticket view/generation
* `feedback.php` – Feedback form
* `payment.php` – Payment simulation
* `reset-pwd.php` – Password reset functionality

---

### 📄 License

This project is for learning, demo, or academic use. Contributions and enhancements are welcome.
