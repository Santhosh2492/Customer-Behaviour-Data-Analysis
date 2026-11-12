# Customer Shopping Behavior – Data Analytics Project

## 1. Overview

This project focuses on analyzing customer shopping behavior to identify purchasing patterns, customer preferences, and business insights.

The project follows an end-to-end data analytics workflow, starting with data exploration and cleaning using Python, followed by data analysis using MySQL, and finally creating an interactive Power BI dashboard to visualize key business metrics.

A comprehensive analytical report and project presentation were also prepared to communicate the findings and business recommendations.

**Project Objective:**

- Understand customer purchasing behavior.
- Identify trends across product categories.
- Analyze customer segments and purchasing patterns.
- Evaluate discount usage and its impact on sales.
- Generate actionable insights to support business decisions.

## 2. Dataset

The project uses a Customer Shopping Behavior dataset containing customer-level shopping information.

The dataset includes details such as:

- Customer ID
- Age and Gender
- Product Category and Item Purchased
- Purchase Amount (USD)
- Review Rating
- Shipping Type
- Discount Applied
- Promo Code Used
- Previous Purchases
- Frequency of Purchases
- Subscription Status

The dataset was initially explored and cleaned to ensure data quality and consistency before performing further analysis.

## 3. Tools & Technologies

| Tool                 | Purpose                                       |
| -------------------- | --------------------------------------------- |
| Python               | Data exploration, cleaning, and preprocessing |
| Pandas & NumPy       | Data manipulation and transformation          |
| Matplotlib & Seaborn | Exploratory Data Analysis and visualization   |
| MySQL                | SQL queries and business analysis             |
| Power BI             | Interactive dashboard development             |
| Gamma AI             | Project presentation creation                 |
| Jupyter Notebook     | Python development environment                |

## 4. Project Workflow

### Step 1: Data Loading and Exploratory Data Analysis (Python)

- Imported the dataset using Pandas.
- Examined dataset dimensions, column names, and data types.
- Analyzed statistical summaries.
- Identified missing values and duplicate records.
- Explored customer demographics and purchasing patterns.
- Created visualizations to understand trends and distributions.

### Step 2: Data Cleaning and Preprocessing (Python)

- Handled missing and null values.
- Checked and removed duplicate records where necessary.
- Corrected data types and inconsistent values.
- Created additional analytical columns, including age groups and purchase frequency in days.
- Prepared the cleaned dataset for SQL analysis.

### Step 3: SQL Analysis (MySQL)

Imported the cleaned dataset into MySQL and performed business-focused analysis using SQL.

Key SQL concepts used:

- SELECT, WHERE, GROUP BY, and ORDER BY
- Aggregate functions (COUNT, SUM, AVG)
- CASE statements
- Subqueries
- Common Table Expressions (CTEs)
- Data segmentation and filtering

**Business questions explored:**

- What are the most popular product categories?
- Which customer segments generate more purchases?
- How do discounts influence purchase amounts?
- What is the average purchase amount across shipping types?
- Which categories attract new, returning, and loyal customers?
- What purchasing patterns can be identified across customer groups?

### Step 4: Dashboard Development (Power BI)

Developed an interactive Power BI dashboard to present key performance indicators (KPIs) and business insights.

**Key dashboard metrics:**

- Total Number of Customers
- Average Purchase Amount
- Average Review Rating

**Dashboard visualizations:**

- Customer purchasing trends
- Product category analysis
- Customer segmentation
- Purchase distribution
- Shipping type analysis
- Discount and promotional code usage

Interactive filters and slicers were incorporated to enable users to explore the data from different perspectives.

### Step 5: Report Preparation

Prepared a structured analytical report covering:

- Project objectives
- Dataset description
- Data cleaning methodology
- Exploratory data analysis
- SQL analysis and findings
- Dashboard insights
- Business recommendations

### Step 6: Project Presentation (Gamma AI)

Created a professional project presentation using Gamma AI to communicate:

- Project overview and objectives
- Tools and technologies used
- Data analytics workflow
- Key analysis and findings
- Dashboard highlights
- Business insights and recommendations

## 5. Power BI Dashboard

The Power BI dashboard provides an interactive overview of customer shopping behavior and purchasing patterns.

**Dashboard Highlights:**

- KPI cards for important business metrics.
- Category-wise purchasing analysis.
- Customer segmentation and behavior.
- Shipping and discount analysis.
- Interactive slicers for data exploration.

## 6. Key Results and Business Insights

The analysis helps identify:

- Customer purchasing patterns across different product categories.
- Differences in purchasing behavior between new, returning, and loyal customers.
- The relationship between discounts, promotional codes, and purchase amounts.
- Customer preferences for different shipping methods.
- Opportunities to improve customer engagement and purchasing experience.

**Business Recommendations:**

- Develop targeted marketing strategies for different customer segments.
- Use customer purchasing patterns to improve promotional campaigns.
- Focus on popular product categories to optimize sales strategies.
- Improve customer retention through personalized offers.
- Use customer feedback and review ratings to identify improvement opportunities.

## 7. Project Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── data/
│   ├── customer_shopping_behavior.csv
│   └── cleaned_customer_data.csv
│
├── notebooks/
│   └── customer_behavior_analysis.ipynb
│
├── sql/
│   └── customer_analysis.sql
│
├── dashboard/
│   └── customer_behavior_dashboard.pbix
│
├── reports/
│   └── project_report.pdf
│
├── presentation/
│   └── project_presentation.pdf
│
├── images/
│   └── dashboard.png
│
└── README.md
```

## 8. How to Run the Project

### Prerequisites

Install the following tools:

- Python 3.x
- Jupyter Notebook
- MySQL Server and MySQL Workbench
- Power BI Desktop

### Step 1: Clone the Repository

```bash
git clone <your-github-repository-url>
```

Navigate to the project directory:

```bash
cd Customer-Shopping-Behavior-Analysis
```

### Step 2: Install Required Python Libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Step 3: Run Python Analysis

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the analysis notebook and execute the cells to perform EDA, data cleaning, and preprocessing.

### Step 4: Run SQL Queries

- Open MySQL Workbench.
- Create a database for the project.
- Import the cleaned dataset.
- Open the SQL script from the `sql` folder.
- Execute the queries to perform business analysis.

### Step 5: Open Power BI Dashboard

- Open Power BI Desktop.
- Load the cleaned dataset or connect to MySQL.
- Open the `.pbix` dashboard file.
- Refresh the data if required.
- Explore the dashboard using interactive filters and slicers.

## 9. Deliverables

The final project includes:

1. Python notebook containing EDA and data cleaning.
2. Cleaned customer shopping dataset.
3. MySQL queries for business analysis.
4. Interactive Power BI dashboard.
5. Project documentation and analytical report.
6. Professional project presentation created using Gamma AI.

## 10. Conclusion

This project demonstrates an end-to-end data analytics workflow using Python, MySQL, and Power BI.

By combining data cleaning, exploratory analysis, SQL-based business queries, and interactive dashboard development, the project transforms raw customer shopping data into meaningful business insights.

It showcases practical skills in data analysis, data preprocessing, SQL querying, data visualization, and business reporting.

---

**Author:** Santhosh

**Project:** Customer Shopping Behavior Analysis

**Skills:** Python | SQL | MySQL | Power BI | Exploratory Data Analysis | Data Cleaning | Data Visualization | Business Intelligence
