# Library Management System Database

## Description

This project implements a fully-featured relational database schema for a Library Management System using MySQL. It allows for the management of books, authors, genres, library members, book loans, and reservations. The database is designed with appropriate tables, columns, data types, constraints (Primary Keys, Foreign Keys, NOT NULL, UNIQUE), and relationships (one-to-many and many-to-many) to ensure data integrity and efficient management of library operations.

## How to run/setup the project (or import SQL)

1.  **Prerequisites:** Ensure you have a MySQL server installed and running.
2.  **Create Database (Optional):** You can create the `LibraryManagementSystem` database manually using a MySQL client or the command line:
    ```sql
    CREATE DATABASE LibraryManagementSystem;
    USE LibraryManagementSystem;
    ```
3.  **Import SQL:** Use a MySQL client (e.g., MySQL Workbench, Dbeaver, command line) to execute the `LibraryManagementSystem.sql` file.

    * **Using MySQL command line:**
        ```bash
        mysql -u <your_username> -p LibraryManagementSystem < LibraryManagementSystem.sql
        ```
        Replace `<your_username>` with your MySQL username. You will be prompted for your password.

    * **Using MySQL Workbench:**
        1.  Connect to your MySQL server.
        2.  Open a new query tab.
        3.  Open the `LibraryManagementSystem.sql` file.
        4.  Execute the entire script.

## Screenshot or link to your ERD

[Link to your ERD image or embed the image here if possible]

*(You would typically use a database design tool like MySQL Workbench to generate an Entity-Relationship Diagram (ERD) based on the schema defined in the SQL file and include a screenshot or a link to it in your README.)*

## Repo Contents

* **`LibraryManagementSystem.sql`**: This file contains the SQL statements to create the tables and define the database schema for the Library Management System (for Question 1).
