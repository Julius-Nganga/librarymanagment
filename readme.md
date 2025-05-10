# Library Management System Database

## Description
This database manages library operations, including book cataloging, member registrations, and loan tracking. It supports:
- Storing book details (ISBN, title, publication year).
- Tracking authors and categories for books.
- Managing member information.
- Recording book loans with due dates and return status.

## Setup Instructions
1. **Prerequisites**: Install MySQL Server.
2. **Create Database**:
   ```sql
   CREATE DATABASE library_db;
   USE library_db;