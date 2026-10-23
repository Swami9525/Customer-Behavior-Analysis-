Customer Shopping Behavior Data Analytics Project

📌 Overview

This project analyzes customer shopping behavior to understand purchasing patterns, customer preferences, product performance, and discount usage.

The project follows an end-to-end data analytics workflow, starting with data loading and cleaning in Python, followed by Exploratory Data Analysis (EDA), SQL-based analysis, and interactive dashboard development in Power BI. A final business report and presentation are created to communicate key insights and recommendations.

Project Goal: Transform raw customer shopping data into meaningful business insights that support data-driven decision-making.

📂 Dataset
The project uses a customer shopping behavior dataset containing information about customer demographics, product categories, purchase amounts, discounts, ratings, and shopping preferences.

Key columns include:
Customer ID
Age and Gender
Category and Item Purchased
Purchase Amount (USD)
Discount Applied
Promo Code Used
Review Rating
Shipping Type
Purchase Frequency
Payment Method
Previous Purchases

🛠️ Tools & Technologies

Python: Data cleaning, transformation, and EDA
Pandas & NumPy: Data manipulation and analysis
SQL: Business queries and data analysis
PostgreSQL: Database storage and querying
Power BI: Interactive dashboards and KPI reporting
Jupyter Notebook / Anaconda: Python development environment
Gamma: Business presentation creation
GitHub: Project documentation and version control

🔄 Project Workflow

1. Data Loading

Imported the CSV dataset into Python using Pandas.
Inspected the dataset structure, column names, and data types.
Checked the number of rows and columns.

2. Data Cleaning & Transformation

Identified and handled missing values.
Checked for duplicate records.
Standardized column names and data formats.
Handled inconsistent categorical values.
Created additional analytical columns, such as purchase frequency in days and customer age groups.
Prepared the cleaned dataset for further analysis.

3. Exploratory Data Analysis (EDA)

Analyzed customer demographics and shopping preferences.
Examined purchase amounts across product categories.
Investigated discount and promotional code usage.
Explored customer ratings and purchase frequency.
Identified patterns and trends using visualizations.

4. SQL Analysis
Loaded the processed dataset into PostgreSQL and used SQL queries to answer business questions.
Example business questions:
Which product categories generate the highest purchase amounts?
Which customer groups spend the most?
How does discount usage relate to customer purchasing behavior?
Which payment methods are most frequently used?
What is the average purchase amount by category?
Which customer segments show different shopping patterns?
SQL concepts used include filtering, aggregation, GROUP BY, HAVING, CASE, subqueries, and window functions where applicable.

5. Power BI Dashboard
Connected Power BI to the analytical dataset and developed an interactive dashboard to present key performance indicators, trends, and customer insights.

6. Business Report
Prepared a report summarizing the analysis, major findings, business implications, and actionable recommendations.

7. Presentation Using Gamma
Created a professional presentation using Gamma to communicate the project objectives, methodology, dashboard findings, and business recommendations.
📊 Dashboard

The Power BI dashboard is designed to provide an overview of customer purchasing behavior.
Suggested dashboard KPIs and visuals:
Total Customers
Total Purchase Amount
Average Purchase Amount
Average Review Rating
Purchase Amount by Category
Customer Distribution by Age Group
Discount Usage Analysis
Payment Method Distribution
Purchase Frequency Analysis
Dashboard features:
Interactive slicers and filters
Category-wise comparisons
Customer segmentation
KPI cards and charts
Clear presentation of business insights

📈 Results & Business Insights

The analysis aims to identify customer purchasing trends and opportunities for improving business performance.
Key areas of investigation include:
Understanding which product categories attract higher customer spending.
Identifying customer segments with different purchasing behaviors.
Evaluating the relationship between discounts and purchase amounts.
Understanding customer preferences for payment and shipping methods.
Examining customer ratings to identify potential areas for service improvement.
Business Value: The project demonstrates how data cleaning, SQL analysis, and interactive visualization can help businesses understand customers and make more informed decisions.
Add specific numerical findings after validating the results from your dataset.

▶️ How to Run

Prerequisites
Install or configure the following:
Python and Jupyter Notebook (or Anaconda)
PostgreSQL
Power BI Desktop
Required Python libraries

Step 1: Clone the Repository
git clone https://github.com/Swami9525/Customer-Behavior-Analysis-
cd customer-shopping-behavior

Step 2: Install Python Libraries
pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2-binary

Step 3: Load the Dataset

Place the CSV file in the project folder and load it in Jupyter Notebook:
import pandas as pd

df = pd.read_csv("customer_shopping_behavior.csv")
df.head()

Step 4: Clean and Analyze the Data
Run the notebook cells to inspect, clean, transform, and analyze the dataset.

Step 5: Load Data into PostgreSQL

Create a database in PostgreSQL and use SQLAlchemy to connect Python to the database. Load the cleaned dataset into the appropriate table.
Keep database credentials private and use environment variables or secure credential prompts.

Step 6: Run SQL Queries
Open your SQL editor and execute the queries included in the project's SQL scripts.

Step 7: Open the Power BI Dashboard
Open the .pbix file in Power BI Desktop, configure the database connection if necessary, and refresh the data.

Step 8: Review the Report and Presentation
Open the project report and Gamma presentation to review the business findings and recommendations.

📁 Suggested Repository Structure

customer-shopping-behavior/
│
├── data/
│   └── customer_shopping_behavior.csv
│
├── notebooks/
│   └── customer_shopping_analysis.ipynb
│
├── sql/
│   └── customer_shopping_analysis.sql
│
├── powerbi/
│   └── customer_shopping_dashboard.pbix
├── reports/
│   └── customer_shopping_analysis_report.pdf
│
├── presentation/
│   └── customer_shopping_behavior_presentation.pdf
│
└── README.md

Adjust the folder and file names to match your actual repository.

🚀 Key Skills Demonstrated
Data Cleaning and Preprocessing
Exploratory Data Analysis (EDA)
Python for Data Analytics
SQL Query Writing and Business Analysis
PostgreSQL Database Integration
Power BI Dashboard Development
KPI Analysis and Data Visualization
Business Reporting and Presentation
GitHub Project Documentation

👤 Author
Sairaj Ramesh Waje
Aspiring Data Analyst | Python | SQL | Power BI | Data Visualization
GitHub:https://github.com/Swami9525/Customer-Behavior-Analysis-/edit/main/README.md
