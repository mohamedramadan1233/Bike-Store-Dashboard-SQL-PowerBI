# Bike-Store-Dashboard-SQL-PowerBI
End-to-end Data Analytics project using SQL Server &amp; Power BI (Data Cleaning → Modeling → Visualization → Insights)
This project presents an end-to-end Data Analytics solution using SQL Server and Power BI to analyze sales performance and generate actionable insights.
<img width="1334" height="691" alt="Screenshot 2026-05-04 152333" src="https://github.com/user-attachments/assets/7b5ecd7f-8e60-4b4c-9a97-2622721b2011" />

An interactive dashboard built to track:

- Net Sales
- Orders Volume
- Customer Activity
- Sales by State & Store
- Monthly Trends


🛠️ Tools & Technologies
- SQL Server
- Power BI


  🧠 Data Preparation (SQL View)

A SQL View was created to:

Join multiple tables (Orders, Customers, Products, Stores)
Perform aggregations (Net Sales, Gross Sales, Discounts)
Transform order status using CASE WHEN

This simplified the data model and improved efficiency in Power Bi 


⚠️ Challenge

The dataset didn’t include a Date Table, which limited time-based analysis.



✅ Solution
- Switched from DirectQuery → Import Mode
- Created custom date logic
- Enabled Time Intelligence calculations
- Improved performance


📈 Key Metrics
- Net Sales: 6.9M+
- Orders: 1,415
- Customers: 1,271


📁 Project Files
- Power BI Dashboard (.pbix)
- SQL Script (.sql)


💬 Feedback

I’m always open to feedback and suggestions!
