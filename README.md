# Bikes Sales Analysis

## Table of Contents
- [Project Overview](#project-overview)
- [Project Structure](#project-structure)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Data Analysis](#data-analysis)
- [Data Visualization](#data-visualization)
### Project Overview
---
Welcome to the Bikes Sales project! This project focuses on analyzing sales data from a Bikes Sales Company spanning 2011 to 2013. This data analysis project aims to provide insights into the sales perfomance of a Bikes Sales company. By analyzing various aspects of the bikes sales data, we seek to identify sales performance across different product categories and gain deep understanding of the company's performance.
### Project Structure
---
- [BikesSalesData.xlsx](BikesSalesData.xlsx) :
  
  This file  containing the raw data from [Kaggle](https://www.kaggle.com/). This primary dataset contains two sheets inside, the first sheet named Sales_Location contains the informations about the locations where the sales were made: Postal Code, Country ... The second sheet named Sales contains the informations about sales and product, we can also find the Postal Code column which links this sheet to the Sales_locations sheet
- [BikesSalesProject.xlsx](BikesSalesProject.xlsx):

  The main Excel file containing the data prepartion, data analysis and data visualization in an interactive dashboard.
### Data Cleaning and Preparation
---
- gathered the data from the Sales_locations sheet into the Sales sheet thanks to the PostalCode column which connects the Sales_Location sheet to the Sales sheet. We used the [XLOOKUP](https://support.microsoft.com/en-us/office/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929) for this step
- Correct Spelling checked: The data was the data was spelled correctly
- Checked duplicates: There were no duplicates data
- Checked missing values: There were no missing value
- Converted OrderDate to americain date format
- Created new column named Profit from SalesAmount and TotalProductCost 
- Formatted SalesAmount, TotalProductCost and Profit to dollar currency
- Created table for our data named Sales-Table.
### Data Analysis
---
Data Analysis involved exploring the Bikes Sales data to answer key questions such as:
- What is the overall sales trend by category?
- Which Products are top sellers?
- What is the overall sales by country?
#### To answer these questions :
- We Used Pivot tables to summarize data
- We used the filters to filter data by category, subcategory and Country
### Data Visualization
---
- Created Interactive charts using Excel's build-in tools.
- Developed a dashboard with slicer to filtering data by product category
  
#### Bikes Sales Dashboard
<img width="729" alt="Bikes Sales Dashboard" src="https://github.com/user-attachments/assets/49f9e302-aca0-4d5a-9b02-5e471e69773a" />


  
