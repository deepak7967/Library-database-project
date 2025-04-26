# Library Management System - SQL Project
## About the Project
This is a SQL project where I created a Library Management System from scratch.
It covers everything from setting up the database, inserting sample data, and running important queries to manage books, members, staff, issued books, and fines.

## Database Structure
Database Name: library

## Tables Created:

BOOKS – Stores details about books.

MEMBERS – Stores details of library members.

STAFF – Information about staff working in the library.

ISSUEDBOOKS – Keeps track of which books are issued to which members.

FINES – Details about fines for late returns.

## Sample Data Added
- books of different genres and years.
- members with their details.
- staff members with different roles.
- book issuance records.
- fine records linked to issued books.

## Main SQL Tasks Done
### Book Related
- Listed all books with less than 3 copies available.

### Member Related
- Found members who have not yet returned their books.

- Listed members who borrowed more than 2 books.

### Book Insights
- Displayed the top 5 most issued books.

- Found books that were never issued.

### Staff Performance
- Counted the number of books issued by each staff member.

- Identified staff who haven't issued any books yet.

### Inventory Insights
- Found genres with the highest number of books in stock.

### Time-Based Analysis
- Found members who returned books late.

- Listed books issued in January 2024.

How to Run
- Create the database:
- CREATE DATABASE library;
- Create all the tables mentioned above.
- Insert the sample data provided.
- Execute the queries one by one to see the results.

## Key Highlights
- Proper use of Primary Keys and Foreign Keys for linking tables.

- Used JOINs, GROUP BY, ORDER BY, Aggregate Functions, and WHERE conditions.

- Performed Date-based filtering using the BETWEEN clause.

## Conclusion
Through this project, I got good hands-on experience with SQL basics as well as slightly advanced queries.
It also helped me understand how real-world systems like libraries manage their data using databases.

Thank you!
