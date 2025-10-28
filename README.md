# Customer-Age-vs-Tenure
Users can see how long customers have been with the bank, broken into four tenure buckets.  They can view debit transaction intensity in grouped ranges.  They can analyze total spending patterns across tenure.  They can drill down into specific age ranges using radio buttons.  They can filter everything by bank number, age group, and balance range.
Overview

This project presents an interactive Tableau dashboard that analyzes customer behavior, engagement, and loyalty using synthetic banking data.
The goal is to visualize how factors like tenure, age, spending, and transaction frequency interact to reveal customer retention patterns and spending trends.

The dataset consists of 5,000 unique customer records, each representing an account profile with variables such as account number, bank number, tenure, balance, debit transactions, and total dollar amount spent.

This dashboard is a perfect example of data storytelling — turning raw transactional data into actionable business insights.

💡 Key Insights & Business Questions

This Tableau dashboard answers key business questions such as:

🕐 How long have customers stayed with the bank?

💳 Do customers with longer tenure spend more money or make more transactions?

👥 How do age and account longevity relate?

💵 What is the average balance maintained by different tenure groups?

🏦 How does customer behavior vary across different banks or branches?

⚙️ Features & Functionality
🎯 1. Tenure Buckets

Customers are segmented into four groups based on how long they’ve been with the bank:

1–5 years (New Customers)

6–10 years (Established)

11–15 years (Loyal)

16+ years (Long-Term Customers)

This view helps visualize retention patterns and customer lifecycle.

💳 2. Debit Transaction Buckets

Grouped by total number of debit transactions:

1–50 transactions

51–100 transactions
This helps identify low-activity vs. high-activity account holders.

💵 3. Total Dollar Amount Spent (By Tenure)

Shows how customer spending changes with tenure — helping detect trends like:

Do long-term customers spend more?

Are newer customers still ramping up activity?

👥 4. Age vs. Tenure Analysis

Customers are grouped into age ranges:

18–24 years

25–34 years

35–56 years

Interactive radio buttons let you explore tenure distribution within each age group.
This feature uncovers how age demographics influence customer loyalty.

🧾 5. Dynamic Filters

Global filters enable user-driven exploration:

Bank Number → Filter by branch or institution

Age Range → Filter by customer demographic

Balance Range → Filter by financial activity

All filters are applied across the entire dashboard for synchronized insights.

📈 6. KPI Summary Cards

Quick-glance metrics at the top of the dashboard:

Total Customers

Average Tenure (Years)

Average Spend ($)

Average Balance ($)

These KPIs provide a concise overview of customer engagement and account performance.
Technical Details

Tools Used:

Tableau Desktop 2024+

Microsoft Excel (Synthetic data source)

Calculated Fields for:

Tenure Bucket

Debit Transaction Bucket

Age Range

Balance Range

Dollar Spend by Tenure

Data Columns:

Variable	Description
Acct Number	Unique account identifier
Bank Number	Identifier for bank/branch
Total Debit Transaction	Count of debit transactions
Total Dollar Amount Spent	Total money spent per account
Balance Avg Calculation	Average balance maintained
Account Open Date	Used to compute tenure
Age Calculation	Customer’s age in years
🖼️ Dashboard Layout

The dashboard is structured into three clean sections:

Top: KPI summary and filters

Middle: Tenure, Spend, and Transaction charts

Bottom: Age vs Tenure interactive visualization

All visuals are styled with consistent color themes, spacing, and tooltips for a professional and executive-ready presentation.

🚀 How to Use

Download the Tableau packaged workbook:
Tenure.twbx

Open it in Tableau Desktop or Tableau Public.

Interact using filters and age radio buttons to explore insights.

📊 Example Insights

Most customers are in the 1–5 year tenure range.

Customers with 11–15 years tenure show the highest spending patterns.

Younger customers (18–24) typically fall into the 1–5 year range, indicating newer relationships.

High balance customers tend to have longer tenure and higher transaction counts.

🧩 Future Enhancements

Integrate real-world anonymized data for richer insights.

Add predictive modeling using Tableau Extensions (e.g., customer churn prediction).

Deploy to Tableau Server or Tableau Public with embedded dashboards.

👨‍💻 Author

Hiranmaya Datta
Senior Data Engineer | Tableau, Azure, Snowflake, Python, Databricks
