# 📚 LibraryManagementDB

## Project Overview
Our database contains book data, checkout data, and book availability data to help students access the information they need and keep availability information at library staff's fingertips.

## Project Purpose
This database was created to consolidate all library book information into a single, structured location. Students and library staff are our key stakeholders who benefit the most from this system.

## Technologies Used
* **MySQL Workbench** – Used to write and execute SQL scripts
* **Microsoft Excel** – Used to create and structure sample data

## Database Features
Our database allows students and library staff to easily track book availability by storing:
* Book details, book copies, and publisher information
* Active student reservation records
* Complete student borrowing and checkout history

## Database Design
<img width="617" alt="Library Management ERD Diagram" src="https://github.com/user-attachments/assets/d7827329-0d0b-47be-8da1-4410c2d92a38" />



## Project Structure
Our files are organized into three primary directories:
* `docs/` – Contains project documentation and requirements used to guide our development process.
* `sql/` – Contains all SQL scripts used for creating tables, inserting sample data, and executing queries.
* `design/` – Contains the Entity-Relationship Diagram (ERD) and raw design files.

## How to Run the SQL Scripts
To set up and run this database locally, follow these steps using **MySQL Workbench**:

1. Clone or download this repository to your local machine.
2. Open **MySQL Workbench** and connect to your database server.
3. Open and execute `sql/create_tables.sql` to generate the database schema and tables.
4. Open and execute `sql/insert_data.sql` to populate the tables with sample data.
5. (Optional) Run `sql/queries.sql` or `sql/stored_procedures.sql` to test database functionality.

## Team & Contributions
| Team Member | Role & Responsibilities |
| :--- | :--- |
| **Anh Ngoc Phuong Do** | Database Designer & Manager |
| **Sesilina Lane** | Database Designer & Manager |
