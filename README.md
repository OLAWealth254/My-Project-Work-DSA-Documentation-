# My-Project-Work-DSA-Documentation-
This is where I started my portfolio building while taking my  Data Analysis class with Incubator Hub

 I have learnt quite a number of things ranging from Microsoft Excel, SQL, to Power BI and now to My Portfolio Building.

 ## Project Topic :- E-commerce Business Insight Analysis (A Case Study of Amazon Products Review Analysis) 

 ### Project Overview 
  This Data Analysis Project aim to generate business insight that guide products improvement, marketing strategies and customer engagement by analysing product and customer review data. We seek to gather enough insight to make reasonable decisions,which enable us to tell compelling stories around our data from the insight gotten and to know the best performance from our data.

  ### Data Sources 
   The primary source of data used (Amazon Products Review Analysis.csv),It is provided by the Incubator Hub, this is an open source data that can be freely downloaded from an online open source such as Kaggle, FRED or any other data repository site.

   ### Data Cleaning 
The data was cleaned using the following Microsoft Excel Functions 
* Product name column - LEFT function and PROPER Function.
* Category column - Delimiter( Data- Text spilt- Delimiter)
* Products with >50% calculated column ( IF function)
* Price Range (<$200,$200-$500,$500)
calculated column ( IF function was used)
Products with < 1,000 Reviews, Calculated column (IF Function)


   ### Business Questions & Insights 
   * Average Discount Percentage by Category: In the pivot table, use the given discounted percentages and computes average by category.
  
   * Product Count by Category:
A pivot table counted the number of products per category.

* Reviews Count by Category: A pivot table counted by the number of review id by category. 

* Top Rated Products(Highest Average Ratings):
A sorted products by average/ max rating, displayed top results.

* Actual Vs Discounted Price by Category: In pivot table use actual price & discount price, average both price by category.

* Products with > 50% Discount:
Use calculated column to filter products with discounted percentage > 50.

* Distribution of Products Ratings: Used a pivot table to count how many products fall under each rating.

* Total Potential Revenue by Category:  Create Revenue Column.
To get revenue = Actual price x Rating count, and aggregated by category.

* Products Per Price Range($200,$200-$500,>$500):  Binned prices into ranges and create a pivot table with different price range counted by the number of products.

* Impact of Discount on Customer Ratings : Use pivot table to identify and compare the trends flows relating to discounted percentage vs ratings.

* Products with < 1,000 Reviews: Counted all products where rating_count is < 1,000.

* Top Discounted Product Categories:
  Average discount percentage by Ratings and sorted descending.

* Top Rated and Most Reviewed Products: In  pivot table use ratings vs reviews by products.


### Dashboard 
  An interactive Microsoft Excel dashboard was created to visually explore the insights. It includes:
 * Category-wise KPIs
 * Discount & Rating Charts
 * Top Products list
 * Filters by Category,Price, Ratings and Discount.



## Files Included
* Amazon product review analysis.xlsx
* Cleaned Data: Cleaned Version of the original dataset with calculated columns
* Pivot Tables
* Dashboard


  ## How to Use
* Clone or download the repository
* Open Amazon product Review Analysis.xlsx in Microsoft Excel
* Use the filters to explore the dashboard.


## Author 
Olarewaju.O.Gift


