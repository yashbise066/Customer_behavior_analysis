data analytics project showcasing customer analysis using python, sql, and power BI Customer Behavior Analysis Using Python, SQL Server & Power BI Overview

This project analyzes customer purchasing behavior using a structured dataset. The analysis includes data cleaning, exploratory data analysis (EDA), SQL-based business insights, and interactive dashboard development. The goal is to uncover customer trends, purchasing patterns, subscription behavior, and revenue insights that can support data-driven decision-making.

Dataset

The dataset contains customer purchase information, including:

Customer ID Age Gender Product Purchased Category Purchase Amount Location Season Review Rating Subscription Status Shipping Type Discount Applied Previous Purchases Payment Method Purchase Frequency

The dataset was cleaned and transformed before analysis to ensure data quality and consistency.

Tools & Technologies Tool Purpose Python (Pandas, NumPy, Matplotlib, Seaborn) Data Cleaning & EDA SQL Server (SSMS) Data Storage & SQL Analysis SQLAlchemy Python-SQL Server Connection Power BI Dashboard Development Gamma Presentation Creation Jupyter Notebook Analysis Environment Project Workflow

Data Loading Imported dataset into Python using Pandas. Performed initial data inspection. Checked data types and missing values.
Data Cleaning Handled missing values. Removed duplicates. Standardized column names. Created derived features where required. Corrected data inconsistencies.
Exploratory Data Analysis (EDA) Analyzed customer demographics. Examined purchase behavior patterns. Identified top-selling products and categories. Studied customer subscription trends. Evaluated revenue distribution across customer groups.
SQL Analysis (SSMS)
The cleaned dataset was loaded into SQL Server and analyzed using SQL queries.

Sample business questions addressed:

Top-rated products Revenue by customer segment Subscription vs non-subscription spending Shipping type analysis Discount usage patterns Age group contribution to revenue Customer loyalty segmentation 5. Dashboard Development

Built an interactive Power BI dashboard to visualize:

Total Revenue Customer Distribution Top Products Category Performance Subscription Insights Shipping Preferences Customer Demographics Purchase Trends 6. Reporting & Presentation Created a business report summarizing key findings. Developed a presentation using Gamma to communicate insights and recommendations. Dashboard Key KPIs Total Revenue Average Purchase Amount Total Customers Subscription Rate Average Review Rating Visualizations Revenue by Category Top Purchased Products Revenue by Age Group Subscription Status Analysis Shipping Type Analysis Customer Purchase Distribution Key Results Identified the highest-performing product categories. Determined customer segments contributing the most revenue. Compared spending behavior of subscribed and non-subscribed customers. Analyzed the impact of discounts on purchasing patterns. Discovered trends in shipping preferences and customer loyalty. How to Run Clone the Repository git clone https://github.com/yashbise066/customer-behavior-analysis.git cd customer-behavior-analysis Install Required Libraries pip install pandas numpy matplotlib seaborn sqlalchemy pyodbc Run Jupyter Notebook jupyter notebook Load Data into SQL Server Create a database in SQL Server. Update connection details in the notebook. Execute the data loading script. Open Power BI Dashboard Open the .pbix file. Refresh the dataset connection. Explore the interactive dashboard. Project Outcomes

This project demonstrates practical skills in:

Data Cleaning Exploratory Data Analysis (EDA) SQL Query Writing SQL Server Integration Data Visualization Dashboard Development Business Reporting Data Storytelling

Author: Yash Bise: Aspiring Data Analyst Skills Demonstrated: Python, SQL Server, Power BI, Excel, Data Cleaning, EDA, Reporting & Dashboarding
