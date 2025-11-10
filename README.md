# Hospital Management System (HMS) Database

This project models a relational database for a hospital / clinical setting. It captures patients, doctors, appointments, schedules, diagnoses, and medical histories, and demonstrates how to run analytical queries on top of that data.

## Features
- Patient & doctor master data
- Appointment booking & attendance
- Doctor schedules
- Medical history and doctor access logs
- Example analytical queries (patient demographics, most common conditions, doctor workloads)

## Tech
- SQL (MySQL-compatible)
- Uses PK/FK constraints and cascading deletes

## How to Run
1. Create database: `CREATE DATABASE HMS; USE HMS;`
2. Run the table creation script
3. Run the sample `INSERT` statements
4. Run the analytical queries at the bottom

## Notes
- Dates use ISO format (`YYYY-MM-DD`)
- Passwords are plain text for demo purposes only
