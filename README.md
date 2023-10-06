# School Management System

The School Management System is a web application built with Laravel that provides a comprehensive solution for managing various aspects of a school, including student enrollment, class scheduling, attendance tracking, and more.

## Features

- Student management: Add, edit, and delete student records with details such as name, date of birth, address, and contact information.
- Class management: Create and manage classes, assign teachers, and track class schedules.
- Attendance tracking: Record student attendance for each class session and generate reports.
- Exam management: Manage exams, including creating exam schedules, recording grades, and generating report cards.
- Teacher management: Add and manage teacher profiles, including contact information and subjects taught.
- User authentication: Secure user registration and login system with role-based access control.
- Dashboard: A comprehensive dashboard providing an overview of key statistics and information.

## Requirements

- PHP 7.4 or higher
- Laravel 8.x
- MySQL database

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/school-management-system.git# school-management-system.git

2.Navigate to the project directory:
```bash
cd school-management-system
```

3.Install dependencies using Composer:
```bash
composer install
```

4.Create a copy of the .env.example file and rename it to .env. Update the database configuration settings in the .env file with your MySQL credentials.

5.Generate an application key:
```bash
php artisan key:generate
```

6.Run database migrations and seed the database:
```bash
php artisan migrate --seed
```

7.Start the development server:
```bash
php artisan serve
```

8.Open your web browser and access the application at http://localhost:8000.

# Usage

 - Register a new user account or log in using the provided credentials.
 - Explore the various modules and functionalities available in the application.
 - Use the provided documentation or in-app help for detailed instructions on using each feature.

