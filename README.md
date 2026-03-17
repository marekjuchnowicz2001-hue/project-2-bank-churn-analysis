-- Bank Customer Churn Analysis --

1. Overview

This project analyzes customer churn in a bank dataset to understand why customers leave.
The analysis was done using Python, SQL, and Power BI.

The goal was to go through a full data analysis workflow and extract insights 
that could help reduce churn.


2. Tech Stack

- Python (pandas, numpy, matplotlib)
- SQL
- Power BI
- Git & GitHub

3. Project Structure


project-2-bank-churn-analysis/
├── 01-data/
│   └── churn.csv
├── 02-notebooks/
│   └── churn-analysis.ipynb
├── 03-sql/
│   └── churn-queries.sql
├── 04-dashboard/
│   └── Dashboard project 2.pbix
│   └── Dashboard project 2.png
├── .gitignore
└── README.md

4. How to Run

### Clone repository

git clone https://github.com/marekjuchnowicz2001-hue/project-2-bank-churn-analysis.git

### Python analysis (optional)

Open:

02-notebooks/churn-analysis.ipynb

and run all cells.

### SQL analysis

Open:

03-sql/churn-queries.sql

and run the queries in your SQL tool (MySQL Workbench).

### Power BI dashboard

Open:

04-dashboard/Dashboard project 2.pbix

and load the data from:

01-data/churn.csv

5. Key Insights

- Overall churn rate is around 20%, which is relatively high.

- Inactive customers are much more likely to leave than active ones.
  This suggests that engagement is a key factor.

- Customers from Germany have the highest churn rate.

- Female customers show slightly higher churn than male customers.

- Customers with two products are the most stable group.

- Customers with three or more products have very high churn
  (this may be influenced by a smaller sample size).

6. Conclusion

Customer activity and product usage seem to be the main drivers of churn.
Focusing on engagement and better product matching could help reduce customer loss.

7. Dashboard Preview

![Dashboard project 2.png](04-dashboard/Dashboard%20project%202.png)