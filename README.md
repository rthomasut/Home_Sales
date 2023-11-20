# Home Sales SparkSQL Challenge

## Steps Completed

### Step 1: Importing Necessary Libraries and Reading Data
- PySpark SQL functions are imported.
- The `home_sales_revised.csv` data is read into a Spark DataFrame.

### Step 2: Creating a Temporary View
- A temporary table called "home_sales" is created.

### Step 3: Average Price for Four-Bedroom Houses Each Year
- A SparkSQL query calculates the average price for a four-bedroom house sold in each year, rounded to two decimal places.

### Step 4: Average Price of Homes with Three Bedrooms and Three Bathrooms Each Year Built
- A SparkSQL query calculates the average price of homes with three bedrooms and three bathrooms for each year they were built, rounded to two decimal places.

### Step 5: Average Price of Homes with Specific Criteria Each Year Built
- A SparkSQL query calculates the average price of homes with three bedrooms, three bathrooms, two floors, and a size greater than or equal to 2,000 square feet for each year they were built, rounded to two decimal places.

### Step 6: View Rating for Homes Costing $350,000 or More
- A SparkSQL query determines the "view" rating for homes costing more than or equal to $350,000, and the runtime of the query is recorded.

### Step 7: Caching the Temporary Table
- The "home_sales" temporary table is cached.

### Step 8: Querying the Cached Temporary Table
- The query from Step 6 is rerun on the cached temporary table, and the runtime is computed.

### Step 9: Partitioning and Querying Parquet Data
- The home sales dataset is partitioned by the "date_built" field, and the formatted parquet data is read.
- A temporary table for the parquet data is created.
- The query from Step 6 is run on the parquet temporary table, and the runtime is computed.

### Step 10: Uncaching the Temporary Table
- The "home_sales" temporary table is uncached.

### Step 11: Verifying Uncaching
- Verification is performed to ensure that the "home_sales" temporary table is uncached using PySpark.

## Conclusion

This README summarizes the steps completed in the Home Sales SparkSQL Challenge. The Jupyter Notebook contains the detailed implementation and code for each step.

## Requirements

- PySpark 3.5.0
- Jupyter Notebook

## Author

Richard Thomas
