# Big-Mart
Sales Prediction for Big Mart Outlets The data scientists at BigMart have collected 2013 sales data for 1559 products across 10 stores in different cities. 
## Data Dictionary
We have train (8523) and test (5681) data set, train data set has both input and output variable(s). You need to predict the sales for test data set.



## Train file: CSV containing the item outlet information with sales value

### Variable	Description
1. Item_Identifier	Unique product ID
2. Item_Weight	Weight of product
3. Item_Fat_Content	Whether the product is low fat or not
4. Item_Visibility	The % of total display area of all products in a store allocated to the particular product
5. Item_Type	The category to which the product belongs
6. Item_MRP	Maximum Retail Price (list price) of the product
7. Outlet_Identifier	Unique store ID
8. Outlet_Establishment_Year	The year in which store was established
9. Outlet_Size	The size of the store in terms of ground area covered
10. Outlet_Location_Type	The type of city in which the store is located
11. Outlet_Type	Whether the outlet is just a grocery store or some sort of supermarket
12. Item_Outlet_Sales	Sales of the product in the particular store. This is the outcome variable to be predicted.
 

## Test file: CSV containing item outlet combinations for which sales need to be forecasted

### Variable	Description
1. Item_Identifier	Unique product ID
2. Item_Weight	Weight of product
3. Item_Fat_Content	Whether the product is low fat or not
4. Item_Visibility	The % of total display area of all products in a store allocated to the particular product
5. Item_Type	The category to which the product belongs
6. Item_MRP	Maximum Retail Price (list price) of the product
7. Outlet_Identifier	Unique store ID
8. Outlet_Establishment_Year	The year in which store was established
9. Outlet_Size	The size of the store in terms of ground area covered
10. Outlet_Location_Type	The type of city in which the store is located
11. Outlet_Type	Whether the outlet is just a grocery store or some sort of supermarket

## Submission file format

### Variable	Description
1. Item_Identifier	Unique product ID
2. Outlet_Identifier	Unique store ID
3. Item_Outlet_Sales	Sales of the product in the particular store. This is the outcome variable to be predicted.
