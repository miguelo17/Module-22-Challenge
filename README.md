# Module-22-Challenge

## Loading Data:
Reading CSV from S3: We began by reading the home_sales_revised.csv file from an S3 bucket into a PySpark DataFrame.
Converting Data to a DataFrame: We utilized PySpark's ability to process large datasets

## Queries and Aggregation:
Average Price Calculation:
We calculated the average price of homes that fit certain conditions (e.g., 4 bedrooms) using SQL-like queries.
Prices were rounded to two decimal places and formatted with commas as thousands separators.

## Optimizing Data with Caching and Partitioning:
Caching Data:
We cached the home_sales DataFrame to optimize the performance of repeated queries on the same data.
We measured the runtime before and after caching to compare the performance improvement.

## Working with Temporary Tables and Views:
Creating Temporary Tables:
We created temporary tables to hold data in memory for efficient queries
