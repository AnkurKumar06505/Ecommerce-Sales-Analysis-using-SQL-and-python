E-commerce Data Analysis
This project focuses on analyzing an e-commerce dataset to extract valuable insights into customer behavior, sales trends, and product performance. The analysis is performed using Python and MySQL, leveraging various libraries such as Pandas, NumPy, Seaborn, and Matplotlib for data manipulation and visualization.

Project Structure
Connecting to MySQL Database:

Established a connection to a MySQL database using the mysql.connector library to retrieve data for analysis.
Importing Data from CSV to MySQL:

Imported several CSV files into the MySQL database, corresponding to different tables such as customers, orders, sellers, products, geolocation, payments, and order_items.
A Python script was used to:
Dynamically create MySQL tables based on the structure of the CSV files.
Map Pandas data types to SQL data types for accurate table creation.
Replace missing values (NaN) with None to correctly handle SQL NULL values.
Insert data from the CSV files into the MySQL database, handling potential data inconsistencies.
Analysis of Customer Demographics:

Queried and listed all unique cities where customers are located.
Counted the number of customers from each state.
Order and Sales Analysis:

Calculated the total number of orders placed in the year 2017.
Found the total sales per product category.
Determined the number of orders placed per month in 2018, and visualized the data using a bar plot.
Calculated the average number of products per order, grouped by customer city.
Identified the correlation between product price and the number of times a product has been purchased.
Calculated the total revenue generated by each seller and ranked them by revenue.
Payment and Revenue Insights:

Calculated the percentage of orders that were paid in installments.
Computed the moving average of order values for each customer over their order history.
Analyzed cumulative sales per month for each year.
Calculated the year-over-year growth rate of total sales.
Customer Retention and Spending Behavior:

Calculated the retention rate of customers, defined as the percentage of customers who made another purchase within 6 months of their first purchase.
Identified the top 3 customers who spent the most money each year, and visualized the data.

Used in this project
Python: Pandas, NumPy, Seaborn, Matplotlib
MySQL: Data storage and retrieval
Jupyter Notebook: For running and documenting the analysis
Visualization and Reporting
Generated various visualizations to aid in the understanding of data trends and insights, including bar plots for order counts and customer spending.
Reported key findings, such as customer retention rates and the correlation between product price and purchase frequency.
