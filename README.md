# 📚 Online-book-store-SQL-project-
Online Bookstore SQL Project – Designed a PostgreSQL database for managing books, customers, and orders. Imported data from CSVs and wrote SQL queries for insights like revenue, stock, customer activity, and top-selling books. Showcases use of joins, aggregates, and real-world database operations.
📈 Project Flow
Online_Bookstore/
├── csv_files/
│   ├── Books.csv
│   ├── Customers.csv
│   ├── Orders.csv
├── sql_load/
│   ├── create_tables.sql   (all CREATE TABLE statements)
│   ├── import_data.sql     ( COPY commands)
├── queries/
│   ├── basic_queries.sql   (genre filter, stock count, revenue, etc.)
│   ├── advanced_queries.sql (joins, most sold books, remaining stock, etc.)
├── Online_book_store.sql   
├── README.md               


🗂️ Dataset Structure
| Table      | Description                                       |
| ---------- | ------------------------------------------------- |
| Books      | Book details (title, author, genre, price, stock) |
| Customers3 | Customer details (name, email, city, country)     |
| Orders3    | Orders placed, linked to customers & books        |



