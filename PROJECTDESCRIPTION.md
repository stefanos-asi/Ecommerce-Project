# Ecommerce-project
This SQL project conducts time series and cohort analysis on the top 5 best-sellers on an ecommerce database.
Key steps:
1. Profiling and Cleaning:
   -Checked for nulls, duplicate values on description for the same stock_code, cleaned and parsed the columns in order to get them in 
    right structure (e.g. transforming the date column in order to convert it into datetime format)
2. Create a new and cleaned csv and import it
3. Time series analysis key points of each question:
   1st question: Leveragde window functions in order to generate the monthly sales, changed date aggregation into 
   monthly  in order to get the right outcome
   2nd question: Applied case statements in order to get the monthly sales of each product in a pivoted form 
   3rd question: leveraged joins in order to get the total orders for each best-selling product as well as the orders with more products 
   other than the best-selling one
4. Cohort Analysis: Utilized date manipulations and joins in order to generate the returnship rate of each best-selling in a custom interval
