# AirBnB_dashboard_DA_sql_python_power_bi 

Airbnb Market Analysis (2020 vs 2023)
Overview
This project analyzes how the U.S. short‑term rental market changed between 2020 and 2023 using Airbnb listing data. The workflow includes loading and cleaning the dataset in Python, performing exploratory data analysis, running SQL queries in PostgreSQL for deeper business insights, and building an interactive Power BI dashboard. The goal is to understand shifts in pricing, availability, demand, and listing growth to support data‑driven decision‑making for hosts and investors.

Dataset
Rows: ~ 232147 , 226031 (2020) + 2023 dataset appended

Columns: 18

Key Features:
Listing details (ID, room type, price, minimum nights, availability)

Host information (host ID, host name, host listings count)

Location attributes (neighbourhood, city, latitude, longitude)

Review metrics (reviews per month, last review date, total reviews)

Tools Used
Python (Pandas, NumPy, Matplotlib, Seaborn) – Data loading, cleaning, EDA

PostgreSQL – SQL queries for business analysis

Power BI Desktop – Dashboard creation and visualization

Jupyter Notebook / VS Code – Development environment

GitHub – Version control and project documentation

Project Steps
Data Loading (Python) Imported raw CSV files
Inspected structure using df.info() and df.describe()

Data Cleaning & Preparation Handled missing values (e.g., reviews_per_month, host name)
Converted date fields to datetime

Removed inconsistent or unused columns

Created new features (e.g., demand categories, year column)

Exploratory Data Analysis (EDA) Price distribution
Availability patterns

Neighbourhood‑level trends

Room type comparisons

Correlation checks

SQL Analysis (PostgreSQL) Executed business‑focused queries such as:
Revenue by neighbourhood

Room type demand comparison

Price evolution (2020 vs 2023)

New listing growth

High‑volume hosts

Budget neighbourhood identification

Power BI Dashboard Interactive visuals for pricing, demand, availability, and neighbourhood trends
Map visualization using latitude/longitude

Year‑over‑year comparison insights

Final Report Summarized findings, insights, and business recommendations based on the analysis.
📊 Dashboard Preview (Add screenshot here once uploaded)

📈 Results (Key Insights) Significant price and demand shifts between 2020 and 2023

Certain neighbourhoods showed strong recovery and listing growth

Entire homes and high‑demand room types performed better post‑pandemic

Availability dropped in several areas, indicating higher occupancy

Budget‑friendly neighbourhoods attracted more volume‑based bookings

