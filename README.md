📊 Retail Sales Performance Dashboard (Power BI)
📌 Project Overview

This project presents a Retail Sales Performance Dashboard built using Microsoft Power BI to analyze business performance across products, regions, and customer segments.

The dashboard provides interactive visualizations to help stakeholders understand revenue trends, product performance, and segment distribution, enabling data-driven decision making.

🖼 Dashboard Preview
<p align="center"> <img src="dashboard-preview.png" width="900"> </p>

📊 Key Metrics

The dashboard tracks the following important business KPIs:

Total Sales

Total Profit

Overall Profit Margin

Total Units Sold

These metrics help measure the overall performance of the business.

📈 Dashboard Features

The dashboard includes the following visualizations:

• Sales by Country – Identifies high performing regions
• Top 5 Products by Sales – Highlights best selling products
• Monthly Sales Trend – Shows sales growth over time
• Sales by Segment – Analyzes sales distribution across customer segments

Interactive slicers allow users to filter data by:

Country

Segment

Year

📊 Key Insights

• The United States contributes the highest share of total sales.
• The top 5 products generate a large portion of total revenue.
• Sales show an upward trend during the last quarter of the year.
• The Consumer segment contributes the largest share of total sales.

📂 Dataset

The dataset used in this project is the Microsoft Financial Sample dataset, commonly used for Power BI practice.

It contains information related to:

Sales

Profit

Products

Customer segments

Geographic regions

💡 Business Problem

Retail companies often struggle to understand which products, regions, and customer segments generate the most revenue.

Without clear analytical insights, decision-makers cannot easily identify sales trends or high performing products.

This dashboard helps stakeholders quickly analyze business performance and make data-driven strategic decisions.

🧮 DAX Measures Used
Total Sales = SUM(financials[Sales])

Total Profit = SUM(financials[Profit])

Overall Profit Margin =
DIVIDE(
    SUM(financials[Profit]),
    SUM(financials[Sales])
)

Total Units Sold =
SUM(financials[Units Sold])

🛠 Tools & Technologies

Power BI Desktop

DAX (Data Analysis Expressions)

Data Visualization

Interactive Dashboards

Business Analytics

🎯 Skills Demonstrated

This project demonstrates the following data analytics skills:

Data Visualization

Dashboard Design

Business Insights

DAX Calculations

Interactive Reporting

Data Storytelling

🚀 Future Improvements

• Customer segmentation analysis
• Profit trend forecasting
• Advanced DAX calculations
• Integration with SQL database
• Predictive analytics using Python

📂 Project Files

- [Power BI Dashboard](retail-sales-dashboard.pbix)
- [Dashboard Preview Image](dashboard-preview.png)
- [Project Documentation](README.md)

👤 Author

Amit Roy

Aspiring Data Analyst | Power BI | SQL | Data Visualization