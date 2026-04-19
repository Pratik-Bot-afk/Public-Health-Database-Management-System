# Public Health Centre Management System

A database-driven Public Health Centre (PHC) Management System built using PHP, MySQL, and XAMPP.

This project is designed to manage core PHC operations including patient registration, prescription management, lab test records, and staff-related activities using relational database design.

## Features

- Patient Registration
- Patient Search, Edit and Delete
- Prescription Management
- Lab Test Management
- Staff Management
- Relational Mapping using:
  - prescribed_to
  - treats
  - dispenses
  - performed_tests

## Tech Stack

- PHP (mysqli)
- MySQL
- HTML/CSS
- XAMPP
- Git/GitHub

## Project Structure

```text
database/       -> SQL schema and sample data
config/         -> Database connection
patient/        -> Patient CRUD operations
prescription/   -> Prescription module
labtests/       -> Lab test module
staff/          -> Staff module
assets/         -> CSS and static resources
includes/       -> Shared PHP files
```

## Database Setup

1. Start Apache and MySQL in XAMPP

2. Open phpMyAdmin

3. Import:

```sql
database/phc_db.sql
```

4. Configure database connection in:

```php
config/db_connect.php
```

5. Run project:

```text
http://localhost/phc-management-system
```

## Future Enhancements

- PDO implementation
- Authentication/Login
- Report generation
- Advanced search
- Cloud deployment

## Author

Pratik Manwatkar
