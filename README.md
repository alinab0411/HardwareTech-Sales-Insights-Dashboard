## Project Title
HardwareTech Sales Insights Dashboard
## Objective
To automate sales insights for HardwareTech using Power BI, in hopes of reducing manual time and effectively support the sales team and manager in data-driven decision making.
## Dataset
Source: Sales Insights (CodeBasics)
Type: Retail Transactional Database
Database: Sales
Tables: Products, Markets, Customers, Transactions etc.
## Tools & Technologies Used
- MySQL
- Power BI Desktop
- Power Query
- ETL
- DAX (Data Analysis Expressions)
## Discovering Insights
Used MySQL to discover basic sales insights. Utilized 'JOIN','WHERE','DISTINCT' statements and logical operators to discover key insights, and to check for missing data, negative values and redundant enteries.
## ETL, Data Cleaning & Modelling
Sucessfully extracted and loaded the entire sales database from MySQL into Power BI, analyzed the data model using star schema, and transformed sales data using Power Query.
***Data Cleaning:
  - Removed empty cities from 'markets'.
  - Removed 'sales_amount' containing 0 or negative values
  - Changed 'currency' from USD to INR where applicable
  - Removed currency duplication
## Key Charts & Visuals
- Total Revenue
- Total Qunatity Sold
- Total Profit Margin and %
- Monthly & Yearly Revenue Trends
- Top Markets and Customers as per Revenue and Profit Margin % Contribution
- Percentage of qunatity sold across market types
## Key Insights
- Highest sales occured in January and August, 2018.
- Delhi and Mumbai contributed significantly to both Revenue and Profit Margin.
- Highest qunatity of hardware was sold to Electricalsara Stores.
- Brick & Mortar customers contributed to approx. 77% of total revenues.
- The total revenues for HardwareTech are consistently declining since July 2019.
## Outcome
This project simulates a real-world business reporting scenario, using Power BI to generate quick insights for decision-makers. It demonstrates foundational data analysis skills in RDBMS, spreadsheet and visualization tools; an essential skill for any analyst.
