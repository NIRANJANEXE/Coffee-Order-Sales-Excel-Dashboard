This dashboard is made using three tables- ORDERS table, CUSTOMERS table, and PRODUCTS table.
These tables contain the sales details of a period of over four years- 2019, 2020, 2021, 2022.
Procedures used-
1.	Utilized xlookup function to gather data for customer names, email and country columns in the order table using customer table.
2.	Utlized INDEX and MATCH functions to gather data for coffee type, roast type, size and unit price columns in customer table.
3.	Created a new column “Coffee Type Name” and utilized IFS function to fill the full names of the abbreviated names in the coffee type column.
4.	Did the same step for Roast Type column.
5.	Changed the date to a dd-mmm-yyyy format.
6.	Did the same for Size by adding kgs after the value by going to format > custom > clear General > 0.0 “kgs”.
7.	Changed the currency to USD format.
8.	Cleared duplicates.
9.	Created five different pivot tables (shortcut = ctrl + N + V + T).
10.	Created a line chart, pie chart, bar chart, two column charts.
11.	Created a timeline.
12.	Inserted 3 slicers.
