# POWER BI: BUSINESS INSIGHTS 360

## PROJECT OVERVIEW

AtliQ Hardware, a leading provider of computer hardware and peripherals globally, operates through diverse distribution channels such as retail, direct sales, and distributor networks, both online and offline. Despite its global reach, AtliQ faced significant financial setbacks due to reliance on static Excel reports that lacked actionable insights, particularly affecting operations in Latin America.

To address these challenges, AtliQ Hardware has mobilized a dedicated data analytics team to develop a dynamic solution: the Business Insights 360 Power BI dashboard, which is designed to offer real-time, actionable insights crucial for informed decision-making.

[Live Dashboard Link](https://app.powerbi.com/view?r=eyJrIjoiNmJlMzJjMmItMGNlMC00ODgxLTgxYjAtMzU3OThhMjkwNmQ0IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9) <br />


**Tools Used:**
- :white_check_mark:	SQL
- :white_check_mark:	Power BI Desktop
- :white_check_mark:	Excel
- :white_check_mark:	DAX language
- :white_check_mark:	DAX Studio (for report optimization)

**Business Terms:**
-	Data analytics, Data warehouse, OLTP, OLAP 
-	Star schema, Snowflake schema
-	FY- Fiscal Year
-	YTD - Year-to-date, YTG – Year-to-go
-	Pre-invoice deductions, Post invoice deductions
-	Net invoice sales, Gross sales, Net sales
-	COGS- Cost of goods sales, Manufacturing costs, freight costs
-	Gross margin, Gross Margin %, Gross Margin per Unit
-	Net profit, Net profit %
-	Sales quantity, Forecast Quantity
-	Net Error, Absolute Error, Forecast Accuracy

## KEY STEPS

**1. Data Collection and Integration**
- Data from MySQL (Facts and Dimensions) and Excel/CSV files (Targets and Market Share) was integrated into Power BI.
- Utilized Power Query (M Language) for effective data transformation.

**2. Data Modelling and Visualization**
- The project utilized the Snowflake Modelling Technique, connecting fact and dimension tables based on their relationships.
- Calculated columns and measures in Power BI, employing DAX functions such as DIVIDE and SUM, were implemented for driving visualizations across reports.

**3. Creating Reports**
- The dashboard features a central Home page for intuitive navigation to various reports and support resources.<br />

- **Key Integrated Features:**
  - Bookmarks to switch Visuals
  - Page Navigation using Buttons 
  -	Dynamic Titles based on Applied Filters 
  -	KPI Indicators
  -	Conditional formatting of Visual Values
  -	Performance Optimization (Using DAX Studio)

- **Five Dashboards:** 
  -	**Finance View:** With a focus on financial planning, it includes analysis of **_P&L statements_**, **_Net Sales Performance Trends_**, and **_Top-Performing Products and Customers_** based on various parameters.
  -	**Sales View:** Increased sales revenue by developing comprehensive reports on **_Customer and Product Performance (NS, GM%, & COGS)_**, tracking key **_Sales Trends_** and KPIs for improved customer management.
  -	**Marketing View:** Increased brand visibility by analysing **_Regional and Product Market Performance (GM%, NP%, COGS, Operational Expenses, & NP)_**, tracking **_Market Trends_**, KPIs, and leveraging data-driven marketing strategies.
  -	**Supply Chain View:** Improved inventory management by analysing **_Forecast Accuracy_**, **_Net Error_**, and **_Absolute Error_** trends, highlighting key Customer and Product demand metrics for supply optimization.
  -	**Executive View:** Offers a comprehensive real-time dashboard overview of **_Organizational Performance_**, detailing **_Revenue across Divisions, Customers, Products, Channels, and Manufacturer_** insights for decisions.

**4. Deployment**
-	Reports published to Power BI services. 
-	Automatic data refresh using a personal gateway.

---
Please check out the **Full Report** for Further Explanation!<br />
\
Your Thoughts and Feedback are highly appreciated! :smile:<br />
\
**LinkedIn**
