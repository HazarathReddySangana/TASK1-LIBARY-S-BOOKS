# TASK1-LIBARY-S-BOOKS
Designing a library database involves creating tables for books, members, and transactions, followed by performing operations like inserting, updating, deleting, and retrieving data. Below is a step-by-step guide to building this project:

Step 1: Define Database Schema

1. Books Table:

Stores information about books in the library.

Fields: book_id (Primary Key), title, author, isbn, published_year, status (to track availability).



2. Members Table:

Stores information about members who can borrow books.

Fields: member_id (Primary Key), first_name, last_name, email, phone, join_date.



3. Transactions Table:

Records borrow and return transactions for books.

Fields: transaction_id (Primary Key), book_id (Foreign Key), member_id (Foreign Key), borrow_date, return_date.




