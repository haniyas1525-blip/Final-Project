E-commerce Sales Analysis Dashboard
Overview
This project analyzes 34,500 online sales transactions and prepares the data for a Tableau dashboard.

Dataset
Orders: 34,500
Unique customers: 7,903
Unique products: 24,912
Total revenue: ₹5,865,293.05
Return rate: 5.52%
Average order value: ₹170.01
Average delivery time: 4.81 days
Tableau Dashboard
Create these worksheets:

Revenue Trend --- Month vs Revenue, line chart
Profit Trend --- Month vs profit_margin metric, line chart
Customer Growth --- Month vs unique customers, line chart
Category Performance --- Category vs Revenue, bar chart
Regional Performance --- Region with Revenue, Return Rate and Average Delivery
KPI Summary --- Revenue, Orders, Customers, Average Order Value, Return Rate and Average Delivery
Suggested dashboard layout
+------------------------------------------------------+
|             E-commerce Sales Dashboard               |
| KPI  | KPI | KPI | KPI | KPI | KPI                  |
+------------------------------------------------------+
|                 Revenue Trend                        |
+-----------------------------+------------------------+
| Profit Trend                | Customer Growth       |
+-----------------------------+------------------------+
| Category Performance        | Regional Performance  |
+-----------------------------+------------------------+
Files
ecommerce_sales_34500.csv --- original transaction dataset
tableau_monthly_kpis.csv --- monthly Tableau-ready metrics
tableau_category_kpis.csv --- category-level Tableau-ready metrics
tableau_region_kpis.csv --- region-level Tableau-ready metrics
Ecommerce_Sales_Analysis_Report.pdf --- 2-page project report
ecommerce_dashboard_preview.png --- dashboard preview
Important Note
The original requested workflow referred to a file named startup_financial_analysis.csv and fields such as CAC, LTV, LTV_CAC_Ratio, and Run_Rate.

The uploaded dataset does not contain those startup-financial fields. This project therefore uses the actual ecommerce dataset rather than fabricating missing metrics.

If the intended project is the startup financial analysis, replace the source file with the correct startup_financial_analysis.csv and rebuild the requested startup KPI dashboard.

Tools
Python / Pandas for data preparation
Tableau Public for visualization
GitHub for project documentation
