📊 Customer Behavior Analysis
📌 Overview

This project presents an end-to-end data analytics workflow to analyze customer purchasing behavior. It involves data extraction, cleaning, exploratory data analysis (EDA), SQL-based querying, and visualization through an interactive Power BI dashboard.

The objective is to uncover actionable insights related to customer segments, purchasing patterns, and revenue drivers.

📂 Dataset
The dataset contains customer-level transaction data including:
Demographics (e.g., gender, age group)
Purchase details (amount, product, category)
Behavioral data (previous purchases, subscription status)
Shipping preferences and discount usage
The dataset was used to identify patterns in customer behavior and spending.
🛠️ Tools & Technologies
Python: Data loading, cleaning, and EDA (Pandas, NumPy, Matplotlib, Seaborn)
SQL: PostgreSQL / MySQL / SQL Server for querying and analysis
Power BI: Interactive dashboard creation
Gamma: Presentation (PPT) design
Jupyter Notebook: Analysis workflow
⚙️ Project Steps
1. Data Loading (Python)
Imported dataset into Jupyter Notebook
Performed initial inspection and understanding of data
2. Data Cleaning
Handled missing values
Removed duplicates
Standardized column formats and data types
3. Exploratory Data Analysis (EDA)
Analyzed customer demographics and purchase behavior
Visualized trends using charts and graphs
Identified patterns in revenue and product demand
4. SQL Analysis
Loaded cleaned data into SQL database
Performed advanced queries to extract insights such as:
Revenue by gender
High-spending customers using discounts
Top-rated products
Customer segmentation (New, Returning, Loyal)
Subscription vs non-subscription spending
Revenue contribution by age group

Example query:

SELECT gender, SUM(purchase_amount) AS revenue
FROM customer
GROUP BY gender;

More queries are available in the SQL file:

📊 Dashboard

The Power BI dashboard provides:

Revenue analysis across customer segments
Product performance insights
Customer segmentation visualization
KPI tracking (total revenue, average spend, etc.)

The dashboard enables interactive filtering for deeper analysis.

📈 Key Results
Identified high-value customer segments (loyal and repeat buyers)
Found that subscription status influences spending behavior
Highlighted top-performing products based on ratings and sales
Discovered the impact of discounts on purchase patterns
Analyzed revenue distribution across age groups
🚀 How to Run
1. Clone the Repository
git clone https://github.com/your-username/customer-behavior-analysis.git
cd customer-behavior-analysis
2. Run Python Analysis
Open the Jupyter Notebook
Execute all cells to perform EDA and preprocessing
3. Run SQL Queries
Import dataset into PostgreSQL / MySQL / SQL Server
Execute queries from the SQL file
4. View Dashboard
Open the Power BI .pbix file
Refresh data if needed
📎 Project Deliverables
Jupyter Notebook (Python analysis)
SQL query file
Power BI dashboard
Analytical report
Presentation (Gamma PPT)
💡 Conclusion

This project demonstrates a complete data analytics pipeline—from raw data processing to business insight generation and visualization. It highlights the ability to work with multiple tools and present insights in a structured, professional, and impactful way.
