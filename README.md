# Brainwave_Matrix_Intern_task1
🛒 Walmart Sales Data Analysis
📌 Project Overview

This project explores and analyzes Walmart commercial store sales data to gain insights into customer behavior, product performance, and overall business growth. The dataset includes transaction details such as branch, city, customer type, product line, payment method, sales amount, gross income, and customer ratings.

The main goal is to understand sales patterns, customer preferences, and revenue drivers to support better business decision-making.

🎯 Objectives

Analyze sales performance across branches, cities, and product lines.

Compare customer purchase behavior (gender, membership type).

Study payment preferences and their impact on sales.

Identify high-revenue product lines and sales trends.

Evaluate gross income and customer ratings.

📂 Dataset Description

The dataset consists of 1,000 sales transactions from Walmart across 3 branches (A, B, C).

Key Columns:

Invoice ID → Unique transaction ID

Branch → Branch code (A, B, C)

City → Location of the branch

Customer type → Member or Normal customer

Gender → Male / Female

Product line → Product category (e.g., Health & Beauty, Electronics)

Unit price → Price per unit

Quantity → Units purchased

Tax 5% → Tax on purchase

Total → Total bill (including tax)

Date / Time → Transaction date & time

Payment → Mode of payment (Cash, Credit Card, E-wallet)

cogs → Cost of goods sold

gross income → Profit earned

Rating → Customer satisfaction rating (1–10 scale)

🛠 Tools & Technologies

Python → Pandas, NumPy, Matplotlib, Seaborn

SQL → Data querying & aggregation

Power BI / Tableau → Visualization & interactive dashboards

Jupyter Notebook → Data analysis workflow

📊 Analysis Performed

Exploratory Data Analysis (EDA):

Sales distribution by branch and city.

Gender-based and customer-type purchase behavior.

Product line performance (top-selling categories).

Peak sales hours and days (time-based analysis).

Payment method preferences.

Business Metrics:

Gross income by branch and product line.

Average customer ratings by category.

High-value transactions and frequent buyers.

Visualizations:

Sales trend plots (daily/weekly/monthly).

Bar/heatmaps for product line vs revenue.

Pie charts for payment methods and customer types.

📌 Key Insights

Branch C had the highest average gross income.

Female customers spent slightly more on average than males.

E-wallet was the most preferred payment method.

Health & Beauty and Food & Beverages were top-performing product lines.

Evening transactions showed higher average sales compared to mornings.

📈 Deliverables

Cleaned dataset (CSV)

Python scripts & Jupyter notebooks

SQL queries for branch/product analysis

Visualization dashboards (Matplotlib/Seaborn/Power BI)

Insights & business recommendations

🚀 How to Run

Clone the repository:

git clone https://github.com/your-username/walmart-sales-analysis.git


Install dependencies:

pip install -r requirements.txt


Run Jupyter Notebook:

jupyter notebook Walmart_Sales_Analysis.ipynb

📌 Future Enhancements

Build a sales forecasting model (ARIMA/Prophet).

Create an interactive Power BI/Tableau dashboard.

Perform customer segmentation (RFM analysis) for loyalty programs.

📜 License

This project is for educational and research purposes only. Dataset credit: Walmart Sales Data.
