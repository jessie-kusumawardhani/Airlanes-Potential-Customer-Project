# 2.	Airlane Potential Customer Project

The airline company aims to rekindle relationship with potential customers by identifying individuals whose sales have consistently declining by more than 10,000 each year from 2020 to 2023. The information needed were:

1. Customer names
2. Customer IDs
3. Annual sales for each customer, from 2020 to 2023

To facilitate seamless collaboration with fellow data analysts, the SQL queries maintain a straightforward and easy-to-comprehend formulation. This will contribute to a more efficient and cooperative work environment.

Below is the query written to generate necessary information:

![](https://github.com/jessie-kusumawardhani/Airlanes-Potential-Customer-Project/blob/main/Flight%20Company.jpg?raw=true)

CTE was used to pull ID, customer name, year, and sales information, and to left-join flight and user datasets. A parent query was then created to filter customers with sales declining over 10,000. The result of this query is as follows (as sample):

![](https://github.com/jessie-kusumawardhani/Airlanes-Potential-Customer-Project/blob/main/Flight%20Company-table.jpg?raw=true)

As a result, a total of 22 potential customers experiencing declining sales was identified.
