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
  1. **Total Revenue by Month:** We have revenue by month from January to December for the year 2011. November ranked the highest with the total of 1,509,496 USD revenue, while February is the least with 523,632 USD revenue. Upon examination, it is evident that certain months experience significant growth. Specifically, the data indicates consistent revenue in the first 8 months, with an average of around $685k generated during this period. The revenue growth begins in September, with a 40% increase compared to the previous month. This upward trend persists until November when it peaks at 1.5 million USD, the highest level for the year. The information for December is missing, so no definitive findings can be made from it. This study illustrates how the sales of the retail store are influenced by the seasonal patterns typically seen in the final four months of the year.

  <img width="462" alt="Rbymonth" src="https://github.com/user-attachments/assets/bf1a1294-ed28-4d65-a5b0-209a71f3cd11">

  2. **Total Revenue and Quantity by Country:** Excluding the United Kingdom, Netherland ranked the highest generating revenue of 285,446 USD and and quantity amounting to 200,937 while Japan is the least country generating revenue of 37,416 USD and quantity of 26,016 respectively. This illustrates the performance of the top 10 countries with growth potential. Excluding the United Kingdom, which already experiences high demand, the focus is on countries where demand can be further increased. The data analysis reveals that countries like the Netherlands, Ireland, Germany, and France have significant unit sales and revenue. It is recommended to prioritize efforts in these countries to enhance market capture.

  <img width="653" alt="QRbycountry" src="https://github.com/user-attachments/assets/da2e2941-824d-4744-a2c8-58478c32a561">

  3. **Total Revenue by Customer ID:** This analysis was conducted on the top 10 customers with the highest purchase records at the store. Customer ID-14646 is the highest revenue generating customer with a total revenue of 280,206 USD while Customer ID-15311 is the least with revenue of 60,768 USD. This findings indicate that there is minimal variation in the purchases of these top customers. The leading customer in revenue only bought 17% more than the second-highest customer, suggesting that the business does not heavily depend on a select few customers for its revenue generation. This demonstrates that customers have limited bargaining power, placing the business in a favorable position.

  <img width="661" alt="RbycID" src="https://github.com/user-attachments/assets/6c79ff19-311d-40ae-807d-7beeca2e9f1f">

  4. **Total Quantity by Country:** The map chart highlights the regions where revenue has been highest in comparison to those with lower revenue. It is evident that, aside from the UK, countries like the Netherlands, Ireland, Germany, France, and Australia are generating substantial revenue. It is advisable for the company to allocate more resources to these areas to stimulate product demand. Additionally, the map reveals that the majority of sales are concentrated in Europe, with minimal activity in the Americas, Africa, Asia, and Russia showing no demand for the products. Implementing a new strategy to target these regions could significantly enhance sales revenue and profits.

  <img width="650" alt="Qbycountry" src="https://github.com/user-attachments/assets/c6fa2b6d-dab3-40e7-838b-29b5bc615d4b">

## Dashboard

  <img width="958" alt="Tata Dashboard" src="https://github.com/user-attachments/assets/6c53e18b-a60b-4403-ac91-eaae42704857">

## Recommendations

- **Targeted Growth Initiatives:** Focusing on the Netherlands, Ireland, Germany, and France, where a significant volume and revenue base already exists. This will involve localized marketing efforts, collaborations with local retailers, and customized product offerings tailored to these specific markets.
- **Marketing Campaigns:** Building on the substantial revenue growth seen from September to November, it is suggested that targeted marketing campaigns be launched in late August to take advantage of the anticipated seasonally driven surge in sales. This proactive approach will enable us to capitalize on the increased demand and maximize revenue opportunities.
- **Customer Retention:** To ensure a consistent revenue flow, I recommend implementing retention strategies that foster customer loyalty, including the development of loyalty programs, regular communication and follow-ups, and personalized promotions tailored to individual customers' needs and preferences.
- **Promotional Offers:** To capitalize on the peak sales periods, I propose offering limited-time special promotions, discounts, and bundled deals that incentivize customers to make purchases, thereby amplifying revenue growth during these critical months.
- **Enhanced Analytics:** By leveraging cutting-edge data analytics technologies, we will unlock actionable insights into customer behavior, market dynamics, and operational performance. This data-driven intelligence will empower informed decision-making and strategic planning, enabling us to optimize our operations, stay ahead of the competition, and drive long-term growth.
