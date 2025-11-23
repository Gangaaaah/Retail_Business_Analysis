# Retail Business Performance & Profitability Analysis


📅 Day 1 — Data Loading & Setup

Collected the retail dataset (superstore.csv)

Loaded the dataset into a SQLite database (retail.db)

Verified database connection and table creation using Python (sqlite3, pandas)

Ensured data was properly inserted into the sales table

🧹 Day 2 — Data Cleaning & Preprocessing

Checked for missing values across all columns using SQL

Identified and removed exact duplicate rows from the dataset

Standardized data types (e.g., converted order_date & ship_date to datetime)

Cleaned inconsistent values and corrected column formats

Replaced the SQL table with the cleaned dataset (updated sales table)

Re-validated the table by reloading from SQLite

📈 Day 3 — Exploratory Data Analysis (EDA)

Performed univariate, bivariate, and correlation analysis

Generated visualizations for:

Sales distribution

Profit distribution

Quantity distribution

Monthly and yearly sales trends

Category-wise and region-wise performance

Computed category-level, region-level, and segment-level sales/profit metrics

Extracted business insights, including:

Technology category generates the highest sales

Office Supplies has the lowest sales

West region yields highest profit; Central region lowest

Consumer segment is most profitable

Discounts negatively correlate with profit

Sales and profit grow steadily year-by-year
