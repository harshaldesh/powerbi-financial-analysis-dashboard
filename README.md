# powerbi-financial-analysis-dashboard
Interactive Power BI dashboard for Sales &amp; Profit Analysis with KPIs, trend analysis, category &amp; regional insights, and profitability tracking.
📊 Power BI Sales & Profit Dashboard
📌 Project Overview

This project is an interactive Power BI dashboard designed to analyze Sales and Profit performance.
It provides insights into:

Revenue, expenses, gross profit, and net profit

Sales & profitability by category, region, and customer segment

Top-performing and underperforming sub-categories

Monthly/Yearly trends and YoY growth

The dashboard is structured into 3 main pages for clear storytelling and analysis.

🗂 Dashboard Pages
1️⃣ Overview Page

KPIs: Revenue, Expenses, Gross Profit, EBIT, Net Profit

Break-even point analysis

Waterfall chart (Revenue → COGS → Opex → Net Profit)

2️⃣ Sales Analysis Page

KPIs: Total Sales, Orders, Avg. Order Value

Monthly & Yearly Sales Trends

Sales by Category, Region, and Segment

Top 10 Subcategories by Sales

3️⃣ Profit Analysis Page

KPIs: Total Profit, Profit Margin %, Avg. Profit per Order

Profit by Category & Region

Profit Trends (Monthly/Yearly)

Top/Bottom 10 Subcategories by Profitability

📈 Key Visuals Used

Cards → KPIs (Sales, Profit, Margins, Growth)

Bar/Column Charts → Category & Regional analysis

Line Charts → Trend analysis

Waterfall Chart → Revenue → Net Profit flow

Table with Conditional Formatting → Profitability by sub-category

Slicers → Category, Region, Year, Segment

🛠️ Tech Stack

Tool: Power BI Desktop

Dataset: Global Superstore (sample)

Key DAX Measures:

Profit Margin % = DIVIDE([Total Profit], [Total Sales])

YoY Profit % = (This Year Profit – Last Year Profit) / Last Year Profit

Avg Profit per Order = DIVIDE([Total Profit], [Order Count])

📷 Screenshots

(Add screenshots of each dashboard page here – store them in a /screenshots folder)
Example:

🚀 How to Use

Clone this repository

Open the .pbix file in Power BI Desktop

Interact with slicers and filters to explore insights

📌 Insights Derived

Technology drives the highest profit margin, while Furniture struggles.

Certain subcategories (e.g., Tables & Bookcases) are unprofitable despite sales.

Profit margins fluctuate significantly across months, with dips in Q2.

West region contributes the highest profitability among all regions.

🔮 Future Improvements

Add forecasting for sales & profit

Integrate Python/R visuals for advanced analytics

Create a storytelling report page for executive summary

📬 Contact

👤 Your Name: Harshal Deshpande
📧 Email: hudeshpande153@email.com
