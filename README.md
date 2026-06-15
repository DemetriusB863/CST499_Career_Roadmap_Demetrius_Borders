# CST499_Career_Roadmap_Demetrius_Borders
A full-stack PHP/MySQL web application for student course registration, built as a CST499 capstone project.
# Online Course Registration System

A full-stack web application developed as the final capstone project for CST499 
at the University of Arizona Global Campus. Built with PHP, MySQL, and Bootstrap 5, 
the system allows students to register accounts, browse available courses, enroll 
or join a waitlist, view their personal schedule, and drop courses.

## Tech Stack
- PHP 8 (server-side logic, session management)
- MySQL / MariaDB (relational database via XAMPP)
- Bootstrap 5 (responsive frontend)
- Apache (local development via XAMPP)

## Features
- Secure user registration and login (bcrypt password hashing)
- Course browser with real-time capacity bars
- Enrollment with automatic waitlist promotion when seats open
- Personal schedule dashboard with drop functionality
- Session-based access control on all authenticated pages
- SQL injection prevention via prepared statements

## Database
Four-table schema: `users`, `courses`, `enrollments`, `waitlist`
Foreign key constraints with ON DELETE CASCADE for referential integrity.

## Setup
1. Install XAMPP and start Apache + MySQL
2. Copy project folder to `htdocs/course_registration/`
3. Open phpMyAdmin and run `database_setup.sql`
4. Visit `http://localhost/course_registration/`

## Project Context
Developed following a full software development lifecycle:
requirements gathering (SRS), UML design modeling (use case, 
class, and sequence diagrams), implementation, and testing.
