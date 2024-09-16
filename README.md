# CSV to MySQL Database Importer & Query Execution

This project imports multiple CSV files into a MySQL database and allows for SQL query execution to retrieve insights. The project connects to a MySQL server and uploads CSV data into corresponding tables. Additionally, it demonstrates how to execute SQL queries in Python to fetch and analyze the data.

## Project Overview

This Python script automates the process of importing several CSV files into a MySQL database. Once the data is imported, it allows the execution of SQL queries, such as fetching unique customer cities, and outputs the results in a pandas DataFrame for further analysis.

## Files Included

The following CSV files are imported into the corresponding MySQL tables:

- `customers.csv` → `customers` table
- `orders.csv` → `orders` table
- `sellers.csv` → `sellers` table
- `products.csv` → `products` table
- `geolocation.csv` → `geolocation` table
- `payments.csv` → `payments` table
- `order_items.csv` → `order_items` table

## Prerequisites

Ensure the following are installed:

1. **Python 3.x**
2. **MySQL Server** running locally or remotely
3. **Python Libraries**:
    - `pandas`
    - `mysql-connector-python`

Install the required libraries using:

```bash
pip install pandas mysql-connector-python
