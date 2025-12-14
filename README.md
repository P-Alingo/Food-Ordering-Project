# UniEats – University Food Ordering System

UniEats is a web-based food ordering system built with Laravel to improve the dining experience within university campuses. The platform enables students and staff to order meals online while allowing food vendors and administrators to manage menus, orders, and users efficiently.

The system addresses common challenges such as long queues, manual order processing, cash-only payments, and paper-based menus by providing a centralized digital solution.

---

## Project Overview

University dining systems often suffer from inefficiencies during peak hours, leading to delays and poor user experience. UniEats digitizes the entire food ordering workflow by allowing users to browse menus, place orders online, and enabling vendors to manage orders in real time.

The application follows Laravel’s MVC architecture and integrates modern frontend tooling for a responsive and user-friendly interface.

---

## Key Features

- User authentication and role management (students, staff, vendors, admin)
- Digital menu management
- Online food ordering
- Vendor order management dashboard
- Admin panel for system control
- Responsive design for mobile and desktop
- Secure data handling and validation

---

## Technologies Used

- **Backend:** Laravel (PHP)
- **Frontend:** Blade Templates, Bootstrap, Tailwind CSS
- **Database:** MySQL
- **Build Tools:** Vite, PostCSS
- **Authentication:** Laravel Authentication
- **Testing:** PHPUnit

---

## System Requirements

- PHP 8.0 or higher
- Composer
- Node.js and npm
- MySQL or compatible relational database
- Laravel CLI (optional)

---

## Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/P-Alingo/Food-Ordering-Project.git
cd Food-Ordering-Project

2. Install Backend Dependencies
composer install

3. Install Frontend Dependencies
npm install

4. Environment Configuration
cp .env.example .env
php artisan key:generate


Update the .env file with your database credentials.

5. Database Migration
php artisan migrate


(Optional)

php artisan db:seed

6. Run the Application
php artisan serve
npm run dev


Access the application at:

http://127.0.0.1:8000

Project Structure
Food-Ordering-Project/
├── app/                 # Models, Controllers, Business Logic
├── adminpanel/          # Admin-specific functionality
├── bootstrap/           # Framework bootstrap files
├── config/              # Application configuration
├── database/            # Migrations and seeders
├── public/              # Public assets
├── resources/           # Views, styles, scripts
├── routes/              # Web routes
├── storage/             # Logs and cache
├── tests/               # Automated tests
├── .env.example         # Environment template
├── artisan              # Laravel CLI entry point
├── composer.json        # PHP dependencies
├── package.json         # Frontend dependencies
└── README.md            # Documentation

User Roles

Students & Staff: Browse menus and place food orders

Vendors: Manage menus and incoming orders

Admin: Manage users, vendors, and system configuration

Notes for Reviewers

Demonstrates practical use of Laravel MVC architecture

Focuses on real-world workflow automation

Emphasizes usability, scalability, and maintainability

License

This project was developed for academic and learning purposes.
