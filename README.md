# SpareParts Project

This repository contains the SpareParts web application.

## Overview

- PHP-based web project for spare part management.
- Includes admin, employee, and garage sections.
- Contains front-end HTML/CSS/JS and back-end PHP files.
- Uses a SQL database schema defined in `spareparts.sql`.

## Structure

- `Admin/` - Admin dashboard and management pages.
- `Employee/` - Employee-related assets and pages.
- `Garages/` - Garage user interface and resources.
- `css/`, `js/`, `images/`, `fonts/` - Shared static assets.
- `spareparts.sql` - Database schema and initial SQL data.

## Setup

1. Install a local PHP server (e.g. XAMPP, WAMP).
2. Place the project folder under the web server document root.
3. Import `spareparts.sql` into your MySQL/MariaDB database.
4. Update database connection details in `Admin/connection.php`.
5. Open the application in your browser.

## Notes

- Keep sensitive configuration files out of version control.
- Use `.gitignore` to exclude local development files.
