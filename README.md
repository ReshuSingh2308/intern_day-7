# intern_day-7

Overview
This Jupyter Notebook demonstrates how to connect to a MySQL database, query sales data, and visualize the results using Python. The notebook performs the following key operations:

Installs required Python packages

Establishes a connection to a MySQL database containing sales data

Executes SQL queries to fetch and analyze sales records

Creates visualizations of the sales data using matplotlib

Requirements
Python 3.x

Jupyter Notebook

MySQL Connector/Python (mysql-connector-python)

pandas

matplotlib

Key Sections
1. Database Connection
Installs the MySQL connector package

Establishes a connection to the sales_data database using credentials

2. Data Querying
Executes SQL queries to:

Fetch all sales records from the online sales data table

Get distinct regions from the sales data

Calculate total revenue across all sales

3. Data Visualization
Creates a simple bar chart showing yearly revenue comparison

Demonstrates basic matplotlib plotting functionality

Usage
Install the required packages using pip install -r requirements.txt

Update the database connection parameters with your credentials

Run the notebook cells sequentially to:

Connect to the database

Execute queries

Generate visualizations

Sample Outputs
The notebook includes:

Printed output of sales records

A bar chart visualization of revenue by year
