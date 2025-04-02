# Store-Sales-Data-Cleaning-and-Analysis-with-SQL
Project Store Sales Data Cleaning and Analysis with SQL

Other projects : [Projects Introduction](https://github.com/ViaThanh/1-Projects-Introduction), [Investment Opportunity Analysis](https://github.com/ViaThanh/4-Data-Preprocessing-and-Investment-Opportunity-Analysis), [Users Behaviours Analysis](https://github.com/ViaThanh/3-Netflix-Users-Behaviours-Analysis)
**Summary of Sales Data Analysis Work with SQL**

This report outlines the data cleaning and analysis process performed on a superstore's sales data using Structured Query Language (SQL). This data was sourced from Kaggle [Superstore Sales Dataset](https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting), with the main goal of gaining a deeper understanding of business performance by analyzing sales trends, customer behavior, and the effectiveness of different product lines.

**Work Performed:**

* **Data Cleaning:**
    * Utilized **Stored Procedures** to check for and handle NULL and empty values in the data columns.
    * Removed duplicate rows to ensure data uniqueness.
    * Eliminated rows containing an excessive number of missing values, which could potentially skew the analysis.
    * Standardized text data in columns such as ship mode, country, city, and region to ensure consistency.
    * Imputed missing values in the sales column with appropriate average values based on other order attributes.

* **Data Analysis:**
    * **Sales:** Analyzed the Average Order Value (AOV) over time and across different regions, identified the states with the highest sales, and tracked monthly and yearly Sales Growth Rate, as well as Purchase Frequency.
    * **Customer Segmentation:** Analyzed the Total Sales and Average Order Value (AOV) for each customer, identified the customer segments generating the highest sales and exhibiting the most frequent purchasing behavior. Assessed Customer Lifetime and Customer Lifetime Value (CLTV).
    * **Products:** Identified the top-selling products based on Total Sales and analyzed the Category Contribution to Sales over the years.
    * **Customer Churn Rate:** Calculated the Customer Churn Rate, identified high-value customers who have stopped making purchases, analyzed the churn rate across different customer segments, and investigated potential factors related to customer churn, such as purchased product categories, ship mode, and delivery time.

**Tools Used:**

* Structured Query Language (SQL) was used to perform all data cleaning and analysis tasks.

**Results:**

Through SQL queries, including the use of Stored Procedures during the cleaning process, the report provided detailed insights into sales performance, customer behavior, and product effectiveness. These findings can be used to make more informed business decisions, optimize sales strategies, and improve customer retention.
