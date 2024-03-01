# Home_Sales

** Imported the necessary PySpark SQL functions.
** Read the "home_sales_revised.csv".
** Created a temporary table called home_sales.
** Answerd the following questions using SparkSQL:
   ## Average price (2 decimal place) for 4 bedroom house sold for each year.
   ## Average price (2 decimal place) of a home for each year the home was built, that has 3 bedrooms and 3 bathrooms.
   ## Average price of a home for each year the home was built, that has 3 bedrooms, 3 bathrooms, 2 floors, and is greater than or equal to 2,000 square feet.
   ## Average price of a home per "view" rating having an average home price greater than or equal to $350,000. Run time for this query was 0.50 seconds
** Cache temporary table home_sales.
** Checke if temporary table is cached.
   ## Average price of a home per "view" rating having an average home price greater than or equal to $350,000.
       ## The run time for the cached query was 0.44 seconds which is 6 seconds less that uncached one.
** Partitioned by the "date_built" field on the formatted parquet home sales data.
** Created a temporary table for the parquet data.
   ## Average price of a home per "view" rating having an average home price greater than or equal to $350,000.
   ## The run time for the query was 0.37 seconds which is 13 seconds less that uncached one.
** Uncached the home_sales temporary table.
** Verified that the home_sales temporary table is uncached using PySpark.

