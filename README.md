# Home Sales Analysis with SparkSQL

# Introduction
This project involves using SparkSQL to analyze home sales data and determine key metrics such as average prices for different types of houses, based on various criteria such as number of bedrooms, bathrooms, floors, square footage, and view rating. Additionally, the project explores techniques such as creating temporary views, partitioning data, caching and uncaching temporary tables, and measuring query runtimes.

# Importing and Setup
Import the necessary PySpark SQL functions for the assignment.

# Reading and Creating Temporary Table
Read the home_sales_revised.csv data into a Spark DataFrame.
Create a temporary table called home_sales.

# Analyzing Home Sales Data
Use SparkSQL to answer the provided questions regarding average prices for different types of homes sold each year.

# Caching and Uncaching
- Cache the temporary table home_sales and check if the temporary table is cached.
- Run a query using the cached data and measure the runtime.
- Uncache the home_sales temporary table.
- Verify that the home_sales temporary table is uncached.

# Partitioning and Query Performance
- Partition the home sales data by the "date_built" field on the formatted parquet data.
- Create a temporary table for the parquet data.
- Run a query using the partitioned data and measure the runtime.

# Conclusion
This project demonstrates the use of SparkSQL to analyze home sales data and extract key insights, as well as techniques to optimize query performance through caching and partitioning. The analysis provides valuable information for understanding trends in the real estate market and making informed decisions.
