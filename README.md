# Bikes Sales Analysis

## Table of Contents
- [Project Overview](#project-overview)
- [Project Structure](#project-structure)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Data Analysis](#data-analysis)
- [Data Visualization](#data-visualization)
- [Analysis Results](#analysis-results)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [Access the files](#access-the-files)
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
- created new column CustomerAge by extracting age from OrderDate and Costumer-dob columns using Excel Formula
- created AgeGroup column from CustomerAge column using [Nested IF Excel statements](https://support.microsoft.com/en-us/office/video-nested-if-functions-bdb0ebe2-caff-4914-835b-36796040e303)
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
<img width="731" alt="Bikes Sales Dashboard" src="https://github.com/user-attachments/assets/e51c0f64-dcba-4176-812c-846cd71dfc1d" />

### Analysis Results
---
The analysis results are summarized as follows:
- The company's sales for each Bike category increase with a noticiable peak every year during summer season, month of Jun.
- The mountain bikes category sales increase steadily each year this product category is the best performing category in terms of sales and revenues, placing mountain bikes in the top 3 best-selling subcategory bikes.
- Road bikes category which had achieved the highest sales during the year 2011, experienced a remarkable decrease in sales from the year 2012 and a progressive increase in sales in 2013 but still lower than the sales of the year 2011.
- The United States and Australia countries hold the most of the company's sales in all categories and all Age groupes and generate the greatest revenue.
### Recommendations
---
Based on the analysis, we recommend the following actions:
- Invest in marketing and promotions of all bikes categories during peak season to maximize revenue
- Work with the product and sales team to understand why there was a decrease of sales in Road bikes category from 2012 compared to 2011 sales of the same category.
- Focus on expanding and promoting products in mountain Bikes category and Touring Bikes category.
- Implement a customer segmentation strategy to target customers effectively
### Limitations
---
We do not have much information about customers, such as customer identities, email addresses, ... This does not allow us to perform in-depth analyzes based on customer information, which could allow us to understand customers

### Access the files
---
You can download the main Bikes Sales Project file and Bikes Sales Dataset directly from the repository:

-[Download Bikes Sales Project](BikesSalesProject.xlsx)

-[Download Bikes Sales Dataset](BikesSalesData.xlsx)





  
