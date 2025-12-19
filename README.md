# Task 7: Basic Sales Summary using SQLite and Python
Used SQL inside Python to extract basic sales information such as total quantity sold and total revenue, and display the results using print statements and a simple bar chart.

## Tools Used
- Python
- SQLite (sqlite3 – built into Python)
- Pandas
- Matplotlib
- Google Colab

## Dataset
A small SQLite database file (`sales_data.db`) created with a single table named `sales`, containing:
- product
- quantity
- price

## Steps Performed
- Created a small SQLite database and sales table
- Inserted sample sales data
- Connected SQLite database to Python using sqlite3
- Executed SQL query with SUM and GROUP BY
- Loaded SQL results into a Pandas DataFrame
- Printed the summarized sales data
- Visualized revenue by product using a bar chart
