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

You can interactive with the report [here]()




