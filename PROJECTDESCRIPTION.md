Dataset Source: https://www.kaggle.com/datasets/carrie1/ecommerce-data?resource=download

Description:

This SQL project conducts time series and cohort analysis on the top 5 products of an online store.
   
   Key steps:
1. Profiling and Cleaning:
   Checked for nulls and duplicate values, cleaned and parsed the columns by using text parsing functions,data type transformations and regular expressions

2. Created a new and cleaned csv and imported it

3. Time series analysis key points of each question:

   1st question: Leveraged window functions in order to generate the monthly sales and find the percentage of each of the 5 top products in total monthly sales 
   
   2nd question: Applied case statements in order to calculate the size of difference between the two top products in a pivoted form
   
   3rd question: leveraged joins in order to generate the percentage of orders that the top 5 products were a part of a basket size greater than one 
   
   4th question: Leveraged window functions in order to retrieve the 6-month simple moving average and gain insights on sales trend
   
5. Cohort Analysis: Utilized date manipulations and joins in order to generate the returnship rate of each best-seller in a custom date        interval (3 months)

Conclusion:

The objective of this project was to provide the audience with some key statistics about the top 5 products based on the metrics of sales and orders, in an interval of 13 months. This analysis can be used to draw valuable insights about the best-sellers such as:

--The monthly sales pattern of each product

--The existence of seasonality in their monthly sales

--The relative size of these products sales in relation with whole dataset's sales

--The returnship behaviour of the customers over these products

--The trend of each product's sales using SMA
