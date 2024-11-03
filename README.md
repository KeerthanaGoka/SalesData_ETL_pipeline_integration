# SalesData_ETL_pipeline_integration
ETL pipeline integrating Salesforce with Snowflake via Airbyte and developed Tableau dashboards for real-time sales insights

**Introduction**

This project aims to gain practical experience and knowledge of the role of a Data Engineer along with the tools used in the current industry.


![image](https://github.com/user-attachments/assets/c44ff551-e376-4375-8c9f-9f5080794df4)

**Conclusion**

Overall, this project provided a comprehensive understanding of the data engineering lifecycle and hands-on experience with tools such as Snowflake and Tableau. The experience has given me the confidence to use any ETL and analytical tool in the industry.

**Methodology:**

**Data source:**

CRM data of an e-commerce company for the year 2022 and 2023.

**Data consists of 4 CSV files :**

1. Sales – Fact table 
3. OrderDetail – Dimension table
4. Customer – Dimension table
5. Product – Dimension table

The project was implemented in three stages:

**Project Part 1:**

In Part 1 of the Project, by configuring the automated ETL tool: Airbyte, the CRM Data from
the Source System: Salesforce was loaded into the Destination system: Snowflake.

**Project Part 2:**

In Part 2 of the project, the loaded data by Airbyte, into the staging schema in Snowflake, was cleaned, formatted, and transformed to a usable state. This data is later inserted in the Production environment schema.

Later a connection was established between Snowflake and Tableau Desktop for further analysis on the data.

**Project Part 3:**

In the final phase, deep dive analysis was conducted using Tableau Desktop, and visualizations were published on Tableau Public. The link for the same:

https://public.tableau.com/views/DataEngineeringSales/Dash2?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link

The analysis revealed insights such as the absence of seasonality in sales, the relationship between order quantity and order amount, and the sales/order sizes state-wise. The analysis also identified top-spending customers and profitable products.

**Insights from the visualizations:**

![image](https://github.com/user-attachments/assets/74c5cf10-5f96-42fa-8056-2fdd73218cd5)

![image](https://github.com/user-attachments/assets/13a22ee3-df7c-42e4-900d-87228104d137)

1. From the quarterly sales donut diagram, no seasonality can be seen as all the quarters have almost the same sales.
2. From the animated scatter plot of Order quantity vs Order Amount, it can be inferred that in general order amounts are higher when the quantity ordered is lower.
3. The trends of Order quantity and Order amount may be understood from the trend chart and further forecasting of sales may be done as required.
4. To understand the sales/order sizes state-wise, the treemap of Order amount/Order quantity may be utilized. While Pennsylvania customers gave the highest sales, customers in Illinois have placed the highest number of orders.
5. As part of customer and product analysis, for the customer distribution map, the concentration of customers may be understood, which may be utilized to select the locations for advertisement and such.
6. From the color formatted text table, top spending customers are identified, who may be targeted for further recommendations on discounts and such.
7. From the Brand-wise Orders donut chart, the distribution of sales of products in each brand may be analysed. This would be vital to understand brand performance.
8. The packed bubble chart of the profits prices of each product may help identify profitable products to focus on to increase sales.

**Challenges:**

The project faced some challenges.
• Including the presence of numerous null values in the data affected the visualization results.
• Additionally, since the data used was mock data, the insights derived from it did not reflect any real-world patterns or have any practical implications.

**Conclusion**

Overall, this project provided a comprehensive understanding of the data engineering lifecycle and hands-on experience with tools such as Snowflake and Tableau. The experience has given me the confidence to use any ETL and analytical tool in the industry.


