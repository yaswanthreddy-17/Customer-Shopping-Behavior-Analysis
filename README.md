# Customer Shopping Behavior Analysis

## Overview

This project focuses on analyzing customer shopping behavior and finding useful insights from customer transaction data.

The project covers the complete data analytics process, starting from loading the dataset in Python, cleaning and exploring the data, analyzing the data using SQL, and creating an interactive Power BI dashboard. A project report and presentation were also created to present the findings clearly.

## Dataset

The dataset contains **3,900 rows and 18 columns**.

It includes information related to:

* Customer demographics
* Purchase details
* Product categories
* Subscription status
* Discounts
* Purchase frequency
* Review ratings
* Season and location

## Tools Used

* **Python** – Data loading, cleaning and analysis
* **Pandas** – Data manipulation
* **Matplotlib / Seaborn** – Data visualization and EDA
* **SQL** – Data analysis and business queries
* **PostgreSQL / MySQL / SQL Server** – Database analysis
* **Power BI** – Dashboard creation
* **Gamma** – Project presentation (PPT)
* **MS Excel** – Data checking and supporting analysis

## Steps Performed

### 1. Load Dataset

Loaded the customer shopping dataset into Python using Pandas and checked the structure, columns, data types, and number of records.

### 2. Exploratory Data Analysis

Performed EDA to understand the data and identify patterns.

Some of the analysis included:

* Customer distribution
* Revenue analysis
* Product category analysis
* Age group analysis
* Gender analysis
* Subscription analysis
* Purchase behavior

### 3. Data Cleaning

Cleaned and prepared the dataset before analysis.

The cleaning process included:

* Handling missing values
* Renaming columns
* Checking data types
* Removing inconsistencies
* Preparing the data for database analysis

### 4. Feature Engineering

Created additional useful columns for analysis, such as:

* `age_group`
* `purchase_frequency_days`

### 5. SQL Analysis

Loaded the cleaned data into a SQL database and used SQL queries to answer business questions.

The analysis included:

* Revenue by gender
* Customer segmentation
* Subscription analysis
* Revenue by age group
* Product and category analysis
* Customer purchasing behavior

### 6. Power BI Dashboard

Created an interactive Power BI dashboard to present the main findings.

The dashboard includes:

* Customer/transaction overview
* Average spending
* Average rating
* Revenue analysis
* Sales by category
* Revenue by age group
* Subscription analysis
* Gender analysis
* Interactive filters

### 7. Report and Presentation

Created a project report to document the analysis and findings.

A PowerPoint presentation was also created using **Gamma** to present the project, methodology, insights, and recommendations.

## Dashboard

The Power BI dashboard provides an easy way to explore the customer shopping data using different filters.

### Dashboard Filters

* Subscription
* Gender
* Category
* Shipping

### Main Metrics

* **3.9K** customers/transactions
* **$59.76** average spend
* **3.75★** average rating

## Results

Some of the main findings from the analysis are:

* Male customers generated approximately **2.1× more revenue** than female customers.
* **27%** of customers were subscribers, while **73%** were non-subscribers.
* Customer segments included **Loyal, Returning, and New** customers.
* Loyal customers formed the largest customer segment.
* Young Adults contributed the highest revenue among the age groups.
* Product performance was analyzed across Clothing, Accessories, Footwear, and Outerwear.

## Business Recommendations

Based on the analysis:

* Increase subscription conversion by providing better subscriber benefits.
* Introduce loyalty programs for repeat customers.
* Review discount strategies to maintain profitability.
* Focus targeted marketing on high-revenue customer groups.

## Project Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── data/
│   └── customer_shopping_behavior.csv
│
├── python/
│   └── data_analysis.ipynb
│
├── sql/
│   └── analysis_queries.sql
│
├── powerbi/
│   └── customer_shopping_behavior.pbix
│
├── report/
│   └── project_report.pdf
│
├── presentation/
│   └── project_presentation.pptx
│
└── README.md
```

## How to Run

### Python

1. Clone or download the project.
2. Install the required Python libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

3. Open the Python notebook:

```bash
jupyter notebook
```

4. Open `data_analysis.ipynb`.
5. Load the dataset and run the cells step by step.

### SQL

1. Open PostgreSQL, MySQL, or SQL Server.
2. Create a database.
3. Import the cleaned dataset.
4. Run the SQL queries from the `sql` folder.
5. Review the results.

### Power BI

1. Open the `.pbix` file using Power BI Desktop.
2. Check the data source if required.
3. Refresh the data.
4. Use the dashboard filters to explore the results.

## Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis
* Data Analysis
* Feature Engineering
* Python
* Pandas
* SQL
* PostgreSQL / MySQL / SQL Server
* Power BI
* Data Visualization
* Dashboard Development
* Business Insights
* Report Preparation
* Data Presentation

## Conclusion

This project demonstrates an end-to-end data analytics workflow, from **data loading and cleaning to SQL analysis, Power BI visualization, reporting, and presentation**.

It helped transform raw customer transaction data into meaningful insights that can support better decisions related to **customer subscriptions, loyalty, marketing, discounts, and sales**.
