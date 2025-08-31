# Cloths-Brand-Analysis-
Power BI project analyzing men’s T-shirt sales data with Azure SQL and DAX.  Includes dashboards on discounts, profit %, sales price, and brand variety.
# Power BI Sales Analysis Dashboard  

## Problem Statement  
A Men’s T-shirt retailer wanted to analyze sales data to answer key business questions:  

- Which brands offer the highest discounts and how do they affect sales?  
- Which brands generate the most profit?  
- Which brands have the widest product variety?  
- Which brands are underperforming with low profit margins?  
- How can this analysis support pricing and inventory decisions?  

The dataset was raw and stored in flat files, making analysis difficult without a structured BI solution.  

---

## Solution Approach  
To address the problem, an end-to-end Business Intelligence pipeline was developed using Azure SQL Database for data cleaning and storage, and Power BI for reporting.  

### Step 1: Data Preparation  
- Uploaded the dataset into Azure SQL Database.  
- Cleaned the data by removing duplicates, fixing null values, and standardizing formats.  

### Step 2: Data Transformation in Power BI  
- Connected Power BI Desktop to Azure SQL Database.  
- Created calculated fields using DAX, including:  
  - Discount %  
  - Profit %  
  - Sales Price  
  - Marked Price  

### Step 3: Dashboard Development  
The dashboard was designed with two interactive pages:  

- Page 1: Brand Overview – Lists all available brands in the dataset.  
- Page 2: Insights and Analysis – Contains multiple visuals for business insights:  
  - Bar Chart – Top 5 brands by Average Discount  
  - Area Chart – Top 5 brands by Average Profit %  
  - Donut Chart – Top 5 brands by Varieties  
  - Ribbon Chart – Top 5 brands by Sales Price  
  - Pie Chart – Bottom 5 brands by Profit %  

### Step 4: Publishing  
- The report was published to Power BI Service for interactive use by stakeholders.  

---

## Key Insights  
- NETPLAY had the highest average discount (72%).  
- The Indian Garage Co. led with the maximum product variety (22.87%).  
- Armani Exchange and Brooks Brothers achieved the highest sales prices.  
- London Hills and Fashion delivered strong profit percentage performance (~16%).  
- Urbanout and Indian Terrain showed the lowest profitability, requiring strategic review.  

---

## Tools and Technologies  
- Azure SQL Database – Data storage and preprocessing  
- SQL – Data cleaning and querying  
- Power BI – Dashboard design and visualization  
- DAX – Custom KPI calculations  

---
