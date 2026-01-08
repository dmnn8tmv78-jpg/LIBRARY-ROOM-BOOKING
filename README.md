# Library Room Booking System

## Project Description
The Library Room Booking System is a web-based application that allows students to view and reserve available study rooms in the library. It also provides an admin dashboard for library staff to manage room availability, approve or deny bookings, and view usage reports.

## Features
- Student login and registration
- Room availability checking
- Online room booking
- Automated email confirmation
- Admin dashboard for booking management
- MySQL database integration

## Technologies Used
- Frontend: HTML, CSS, JavaScript
- Backend: PHP, Apache
- Database: MySQL
- Email: PHPMailer with Gmail SMTP

## SMART Requirements
- Booking confirmation stored in the database within 1 minute
- Email confirmation sent within 1 minute after booking
- Real-time admin view of room occupancy with one-click actions

## System Architecture
The system follows a client-server architecture where the frontend communicates with PHP backend scripts that handle validation, database operations, and email notifications.

## 4-Week Development Plan
- Week 1: Planning and UI wireframe design
- Week 2: Database setup and booking form
- Week 3: Admin dashboard and email integration
- Week 4: Testing and final deployment

## How to Run
1. Install XAMPP
2. Place the project folder in `htdocs`
3. Import the SQL file from `/database`
4. Configure database credentials in `config.php`
5. Open `index.html` in your browser
