# 📚 Online Bookstore SQL Project  

A complete SQL project simulating an **online bookstore system**.  
The project demonstrates database creation, data import from CSV files, and SQL queries to analyze sales, customers, and inventory.  

---

## 📊 Project Overview  
This project answers key business questions for a bookstore using SQL queries. It includes:  

- Managing **Books, Customers, and Orders** data  
- Importing data from CSV files into PostgreSQL  
- Writing queries to analyze:  
  - Revenue generated  
  - Customer activity and spending  
  - Top-selling books and genres  
  - Inventory and stock tracking  

The project showcases SQL fundamentals such as **joins, aggregations, GROUP BY, HAVING, and filtering** to replicate real-world business operations.  

---

## 🗂️ Dataset Structure  

| Table      | Description |
|------------|-------------|
| **Books**       | Book details (title, author, genre, year, price, stock) |
| **Customers3**  | Customer details (name, email, phone, city, country) |
| **Orders3**     | Orders placed by customers, linked to books and customers |  

---

## 🧠 SQL Queries Included  

| Query No. | Query Title | Description |
|-----------|-------------|-------------|
| 1 | Fiction Books | Retrieve all books in the "Fiction" genre |
| 2 | Revenue Report | Calculate total revenue from all orders |
| 3 | Top Customers | Find customers who placed at least 2 orders |
| 4 | Best-Selling Book | Identify the most frequently ordered book |
| 5 | Stock Remaining | Compute stock left after fulfilling all orders |
| 6 | Avg Fantasy Price | Get average price of Fantasy genre books |
| 7 | Customer Spending | Find the customer who spent the most |
| 8 | Genre Insights | Total books sold per genre |  

(And more queries for sales trends, expensive books, orders by date, etc.)  

---

## 🧰 Tech Stack  
- **Database**: PostgreSQL (v15+)  
- **Tool**: pgAdmin  
- **Data Source**: CSV files (Books, Customers, Orders)  
- **Editor**: VS Code + PostgreSQL extension  

---

## 📈 Project Flow  

Online_Bookstore/
├── csv_files/
│   ├── Books.csv
│   ├── Customers.csv
│   ├── Orders.csv
├── sql_load/
│   ├── create_tables.sql   (all CREATE TABLE statements)
│   ├── import_data.sql     (COPY commands)
├── queries/
│   ├── basic_queries.sql   (genre filter, stock count, revenue, etc.)
│   ├── advanced_queries.sql (joins, most sold books, remaining stock, etc.)
├── Online_book_store.sql
├── README.md

