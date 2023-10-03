# Contoso Sales Analysis
This project shows the state of the Sales Financial Performance of business during the month, identify growth opportunities and pain points which will help the business plan for the next period.

## Introduction
This is a Power Bi Masterclass project that was organised in the month of August 2023.The project is on sales analysis of a store called **Contoso Stores**. This project shows the state of the Sales Financial Performance of business during the month, identify growth opportunities and pain points which will help the business plan for the next period. 

**_Disclaimer_**: _All datasets and reports do not represent any company, institution or country, but just a dummy dataset to demonstrate capabilities of Power Bi._

## Problem Statement
1.	What is the best and least selling product?
2.	What is the highest selling store?
3.	Details of Customer
4.	Which country has the highest sales?

## Skills/ Concept demonstrated:

The following Power BI features were incorporated.
- DAX,
- Modelling
- Filters
- Drill Through

## Data Gathering and Transformation
The data came in a zip folder as a file and to get the data, Here are the steps i took:
- I Download and Install SQL Server Management Studio (SSMS) and Developer Edition
- Restore the ![Contoso file](https://github.com/victorialolo/Sales-Performance/blob/main/Contoso.100K.bak).
  
Once i got this done successfully, i was able to get the data to Power BI from the SQL Database, i connected to the database that i setup and extracted the table into the Power BI. The the data needed to be transformed and clean for ease of the analysis and it was done using Power Query.


## Data Modelling
The model is a star schema.
There are 5 dimension tables and 1 fact tabel. The dimension tables are all joined to the fact table with a one-to-many relationship. 
![](Data_Model.png)

## Visualization

The report is a 

![](Dashboard.png)

You can interactive with the report [here](https://app.powerbi.com/view?r=eyJrIjoiMWYyZjM0ODYtMjM5Mi00NWUyLThkMTgtMWQzMDEwM2VlYmE0IiwidCI6IjUwODUxMjk2LTliZDEtNGM1Yi05MDllLWY2M2U0OWVmZWEyNSJ9)

## Conclusions and Recommendation
1. At **$380,697.7**, Sat had the highest Total Sales and was 663.04% higher than Sun, which had the lowest Total Sales at **$49,892.3**
2. Across all 7 Day of Week Short, Total Sales ranged from **$49,892.3** to **$380,697.7**
3. United State had the highest sales of **$879,106.3** and Italy generated the least sales of **$23,499.2. This can also be drill down to the customer demography of this countries, the Male gender generated more of the sales compare to the Female gender. We can also see the age(group) that brought in more sales to the business.
4. **Computers** accounts for *8648,923.7** of the total sales making it the highest selling product category for the month with a total order of **455**. Cell phones with **380,932.1** of the total sales, attract customers more as this can be seen in the numbers of customer demands of **479** orders.

## Recommendation
   





