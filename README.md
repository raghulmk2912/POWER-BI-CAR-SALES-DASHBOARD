🚗 Car Sales Performance Dashboard – Power BI
--------------------------------------------------------------------------------------------------------------------------------------------
A fully interactive Car Sales Analytics Dashboard built using Power BI to analyze YTD/MTD Sales, Cars Sold, Average Price, YOY Growth, and regional performance using multiple visual insights.

📌 Project Overview
---------------------------------------------------------------------------------------------------------------------------------------------
This project visualizes car sales data using Power BI.
It includes KPI tracking, weekly sales trends, company-wise insights, and geographic analysis to help businesses make clear, data-driven decisions.

🎯 Objectives
-----------------------------------------------------------------------------------------------------------------------------------------------
Build a dynamic and interactive Car Sales Dashboard.

Track YTD, MTD, and YOY performance for Sales, Cars Sold & Price.

Analyze sales trends across body style, color, company, and regions.

Improve decision-making with clear, visual business insights.


🛠️ Tools & Technologies
----------------------------------------------------------------
Power BI Desktop

Power Query

Excel (for initial cleanup)

DAX Measures

GitHub (project hosting)

🧹 Data Cleaning & Preparation
-------------------------------------------------------------
Performed in Excel & Power Query:

Removed duplicates

Standardized text formats

Checked & fixed missing values

Corrected date and number formats

Renamed columns clearly

Exported cleaned dataset as Cleaned_Car_Sales.xlsx

📊 Dashboard Features & Visuals
---------------------------------------------------------------------------
🔹 KPI Cards

YTD Total Sales

MTD Total Sales

YOY Growth %

YTD vs PTYD Difference

YTD & MTD Average Price

YTD & MTD Cars Sold

🔹 Charts & Visuals

YTD Sales Weekly Trend (Line Chart)

YTD Sales by Body Style (Pie Chart)

YTD Sales by Color (Pie Chart)

Cars Sold by Dealer Region (Map Visual)

Company-wise Sales Trend (Table / Grid)

Detailed Sales Information Table

📈 Insights & Key Findings
-----------------------------------------------------------------------------------------

SUVs generated the highest YTD sales.

White and black were the top-selling car colors.

Southern region performed best in cars sold.

YOY sales showed positive growth overall.

Several weeks showed downward dips suggesting seasonal patterns.

“XYZ Motors” (example) topped YTD revenue among companies.

(Customize these insights based on your actual results.)

🧩 Data Model & DAX Used
--------------------------------------------------------------------------------------------

Key DAX measures used:

YTD Sales = TOTALYTD(SUM('Sales'[Sales Amount]), 'Sales'[Date])
MTD Sales = TOTALMTD(SUM('Sales'[Sales Amount]), 'Sales'[Date])

YOY Sales = 
CALCULATE(
    SUM('Sales'[Sales Amount]),
    SAMEPERIODLASTYEAR('Sales'[Date])
)


(Add more DAX formulas as needed.)

🖼️ Dashboard Screenshots
--------------------------------------------------------------------

Add your dashboard images here.

Example:

![Dashboard Overview](images/dashboard_main.png)
![KPI Section](images/kpi_section.png)
![Sales Trend](images/sales_trend.png)



📌 Conclusion
-------------------------------------------------------------------------------------

This Power BI dashboard provides a clear view of car sales performance, showing trends across time, regions, companies, and car attributes.
It supports smarter decisions in sales strategy, inventory planning, and pricing.

⭐ Author
----------------------------------

M K RAGHUL
--------------
Power BI Developer | Data Analyst
