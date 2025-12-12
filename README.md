📊 Customer Shopping Behavior Analysis – Data Analytics Project


⭐ Overview
This project focuses on end-to-end data analytics using Python, SQL, and Power BI.
It covers the complete workflow of a real-world analytics pipeline:
✔ Loading & exploring data in Python
✔ Data cleaning & preprocessing
✔ Running SQL queries using  MySQL / SQL Server
✔ Building an interactive Power BI dashboard
✔ Preparing a final report & presentation

The goal is to extract meaningful insights about customer shopping behavior and showcase skills in data handling, analysis, visualization, and reporting.

📁 Dataset
The dataset contains customer shopping information, including:
Customer demographics
Item purchased
Product categories
Purchase amount
Shipping type
Review ratings
Subscription status

File format: CSV

🛠️ Tools & Technologies Used
Programming :
Python (Pandas, NumPy, Matplotlib/Seaborn)
Jupyter Notebook

Database :
Can be used on any of the following:
MySQL
SQL Server  

BI & Reporting:
Power BI (Dashboard Visualization)
Microsoft Word (Report)
Gamma App (Presentation)

🔍 Project Steps
1. Load Data in Python

Imported CSV using Pandas

Checked data shape, info, summary stats

Identified missing values and inconsistencies

2. Exploratory Data Analysis (EDA)

Performed:

Univariate analysis (distribution of numerical & categorical features)

Bivariate analysis (category-wise purchase behavior)

Outlier detection

Review rating analysis

Revenue contribution by age, category, subscription status, etc.

3. Data Cleaning & Preprocessing

Filled missing values using mean/median

Standardized category names

Removed duplicates

Converted data types

Exported cleaned data for SQL & Power BI

4. SQL Analysis

Executed SQL queries to derive insights, including:

Customer segmentation

Revenue calculations

Category-wise purchase analysis

Subscription vs non-subscription behavior

Database used: (MySQL / SQL Server — based on requirement)
Cleaned dataset was loaded into the SQL server and queried for insights.

5. Power BI Dashboard

Created an interactive dashboard that includes:

Total customers

Average purchase amount

Average review rating

Revenue by category

Sales by age group

Subscription insights

Filters for category, gender, shipping type, etc.

The dashboard helps visualize trends and interpret customer behavior easily.

6. Final Report

A formal project report was developed (Word/PDF) containing:

Project overview

dataset summary

Exploratory data analysis using python

Data Analysis using SQL

Visualization 

Business Recommendation

7. Presentation (Gamma)

A clean, minimalist PPT-style presentation showcasing:

Problem overview

EDA summary

Dashboard highlights

Recommendations

📈 Results & Insights

Key observations from the analysis:

Clothing & Accessories are top-performing categories.

Young Adults and Adults generate the highest revenue.

Subscription members spend more and shop more frequently.

Average review rating is moderate (~3.7), indicating scope for product improvement.

Shipping type preference varies strongly with product category.

▶️ How to Run This Project
1. Clone the Repository
git clone https://github.com/SujataSukum/Customer_behaviour_analysis.git
cd Customer_behaviour_analysis

2. Run Python Notebook

Install libraries:

pip install pandas numpy matplotlib seaborn

Open Jupyter:

jupyter notebook

Run:
customer_shopping_behaviour_analysis.ipynb

3. Load Data into SQL

Use any database tool (pgAdmin / MySQL Workbench / SSMS):

Create a database

Import the cleaned CSV

Run SQL queries from sql_queries.sql

4. View Power BI Dashboard

Open the file:
Customer_Behavior_Dashboard.pbit

5. View Report & Presentation

Report →Customer-Shopping-Behaviour-Analysis-Report.pdf

Presentation →Customer-Shopping-Behavior-Analysis.pdf
