# TATA-Retail-Store-Analysis
A leading online retail store has experienced impressive revenue growth and is seeking to identify the key drivers behind this success in order to inform strategic planning and optimize future growth initiatives for the upcoming year.

## Table of Contents
- Problem Statement
- The Data
- Tools
- Data Cleaning and Preparation
- Exploratory Data Analysis
- Insights
- Dashboard
- Recommendations

## Problem Statement
The online store is grappling with inadequate revenue data management, which has compromised its ability to make informed decisions and seize business opportunities, ultimately hindering the company's potential for growth and success. Some of the key issues as communicated by the CEO/CMO include;
- Identifying the region generating the highest and lowest revenue.
- The months generating the most revenue, and to know if there is a seasonality in sales.
- To determine the monthly trend revenue and ascertain which months have faced the biggest increase/decrease.
- Knowing the top customers and how much they contribute to the total revenue.

## The Data
The dataset for this project was collected from Forage. It comprises 53,128 rows and 8 columns containing the following information:

- Stock Code
- Description
- Unit Price
- Customer ID
- Country
- Revenue
- Invoice Date

## Tools
- Power Query - Data Cleaning and Preparation
- Tableau - Data Visualization

## Data Cleaning and Preparation
After successfully importing the data into Excel, I moved on to Power Query to clean out the data. This involved implementing the following steps to ensure the data was suitable for analysis.

- Data type check: A thorough examination was conducted to ensure that each column was accurately configured with the correct data type. Where necessary, columns were converted from one data type to another (e.g. text to number) to ensure data integrity and optimal processing.
- Negative values: A quality control process was implemented to identify and rectify errors in the quantity and unit price data. Specifically, any negative values in the quantity column (indicating quantities less than 1 unit) were corrected, as well as any unit prices that were inadvertently entered below $0.
- Duplicate check: No duplicate rows were found in the dataset.
- Outliers: No outliers were detected in the dataset.

## Exploratory Data Analysis
The following were considered for this purpose:

- What are the time series of the revenue data for the year 2011 only?
- What are the top 10 countries which are generating the highest revenue, excluding United Kingdom?
- Who are the top 10 customers generating revenue?
- Which of the countries have the highest demand for the products?

## Insights
  1. **Total Revenue by Month:** We have revenue by month from January to December for the year 2011. November ranked the highest with the total of 1,509,496 revenue, while February is the least with 523,631 revenue. Upon examination, it is evident that certain months experience significant growth. Specifically, the data indicates consistent revenue in the first 8 months, with an average of around $685k generated during this period.
The revenue growth begins in September, with a 40% increase compared to the previous month. This upward trend persists until November when it peaks at 1.5 million USD, the highest level for the year. The information for December is missing, so no definitive findings can be made from it. This study illustrates how the sales of the retail store are influenced by the seasonal patterns typically seen in the final four months of the year.

<img width="462" alt="Rbymonth" src="https://github.com/user-attachments/assets/bf1a1294-ed28-4d65-a5b0-209a71f3cd11">

  2. 
