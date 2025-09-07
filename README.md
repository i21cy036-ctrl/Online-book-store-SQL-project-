# Online-book-store-SQL-project-
Online Bookstore SQL Project – Designed a PostgreSQL database for managing books, customers, and orders. Imported data from CSVs and wrote SQL queries for insights like revenue, stock, customer activity, and top-selling books. Showcases use of joins, aggregates, and real-world database operations.
Here’s your project, step-by-step, and what each part does:

Create the database
Makes a DB named OnlineBookstore. 

Online_book_store

Define tables

Books with columns (Book_ID serial PK, Title, Author, Genre, Published_Year, Price, Stock). 

Online_book_store

Customers3 with customer details (no PK defined). 

Online_book_store

Orders3 with Order_ID serial PK, FKs to Books(Book_ID) and (intended) customers. (Note: it references Customers(Customer_ID) but your table is Customers3.) 

Online_book_store

Quick sanity checks
SELECT * FROM Books/Customers3/Orders3; to view raw table contents. 

Online_book_store

Load data from CSVs
Three COPY commands import rows into Books, Customers3, and Orders3 from your local CSV files. 

Online_book_store

Drop a foreign-key constraint
ALTER TABLE orders3 DROP CONSTRAINT orders3_customer_id_fkey; (likely to bypass FK errors during load). 

Online_book_store

Basic query set (practice/analysis)
Examples: all Fiction books; books after 1950; Canada customers; Nov-2023 orders; total stock; most expensive book; orders with qty>1; orders with amount>20; distinct genres; lowest-stock book; total revenue. 

Online_book_store

Advanced query set

Books sold per genre (JOIN + SUM).

Avg price for Fantasy.

Customers with ≥2 orders (GROUP BY + HAVING).

Most frequently ordered book.

Top 3 expensive Fantasy books.

Quantity sold by author.

Cities of customers who spent > $30.

Top-spending customer.

Remaining stock after orders (LEFT JOIN + COALESCE).
