# Retail Business Performance & Profitability Analysis


📅  — Data Loading & Setup

Collected the retail dataset (superstore.csv)

Loaded the dataset into a SQLite database (retail.db)

Verified database connection and table creation using Python (sqlite3, pandas)

Ensured data was properly inserted into the sales table

🧹 — Data Cleaning & Preprocessing

Checked for missing values across all columns using SQL

Identified and removed exact duplicate rows from the dataset

Standardized data types (e.g., converted order_date & ship_date to datetime)

Cleaned inconsistent values and corrected column formats

Replaced the SQL table with the cleaned dataset (updated sales table)

Re-validated the table by reloading from SQLite

📈  — Exploratory Data Analysis (EDA)

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

📊  — Power BI Dashboard Development

Connected retail.db to Power BI using the SQLite connector

Cleaned and formatted data inside Power BI for reporting

Created the following visualizations:

📦 Sales by Category (Bar Chart)

🌎 Profit by Region (Bar / Map)

👥 Sales by Segment (Pie Chart)

📅 Yearly Sales Trend (Line Chart)

💸 Profit vs Discount (Scatter Plot)

🏆 Top 10 Products by Sales (Bar Chart)

Added slicers for:

Category

Region

Segment

Designed and formatted an interactive dashboard with:

Clear titles

Consistent colors

Proper labels

Filters for easy data exploration

Exported dashboard insights into a summary for reporting
