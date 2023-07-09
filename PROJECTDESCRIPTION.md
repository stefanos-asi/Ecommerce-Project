# Ecommerce-project
Description:
This SQL project conducts time series and cohort analysis on the top 5 best-sellers on an ecommerce database.
Key steps:
1. Profiling and Cleaning:
   -Checked for nulls and duplicate values, clεaned and parsed the columns in order to get them in the
    right structure by using the appropriate text parsing functions,data type transformations and regular expressions 
2. Created a new and cleaned csv and imported it
3. Time series analysis key points of each question:
   1st question: Leveraged window functions in order to generate the monthly sales and find the percent of each product monthly          
   aggregated
   2nd question: Applied case statements in order to get the monthly sales of each product in a pivoted form 
   3rd question: leveraged joins in order to get the percent the orders with more products other than the best-selling one
5. Cohort Analysis: Utilized date manipulations and joins in order to generate the returnship rate of each best-seller in a custom date        interval (3 months)
Conclusion:
The objective of this project was to provide the audience with some key statistics about the top 5 products according to total sales in an interval of 13 months. This analysis can be used to 
