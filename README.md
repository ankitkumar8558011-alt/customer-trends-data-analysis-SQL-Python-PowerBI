# 🛍️ Customer Shopping Behavior Analysis

A complete end-to-end Data Analytics project that analyzes customer shopping behavior using **Python, PostgreSQL, SQL, and Power BI**. The project uncovers purchasing trends, customer segments, product preferences, and business insights to help improve customer engagement and optimize marketing strategies. :contentReference[oaicite:0]{index=0}

---

## 📌 Project Overview

This project analyzes **3,900 customer purchase records** across multiple product categories to identify spending patterns, customer preferences, subscription behavior, and purchase drivers. The analysis combines data cleaning, SQL-based business analysis, and interactive dashboards for decision-making. :contentReference[oaicite:1]{index=1}

---

## 🎯 Business Problem

A retail company wants to understand customer shopping behavior to:

- Improve sales performance
- Increase customer satisfaction
- Build long-term customer loyalty
- Identify purchase trends
- Optimize marketing campaigns
- Improve product strategy

The company is interested in understanding how factors such as:

- Discounts
- Customer Reviews
- Seasons
- Product Categories
- Payment Preferences
- Subscription Status

influence customer purchasing decisions. :contentReference[oaicite:2]{index=2}

---

# 📊 Dataset Information

| Feature | Value |
|----------|-------|
| Total Records | 3,900 |
| Total Columns | 18 |
| Missing Values | 37 (Review Rating) |
| Database | PostgreSQL |

### Dataset contains

- Customer Demographics
- Purchase Information
- Product Categories
- Review Ratings
- Subscription Status
- Discounts
- Shipping Type
- Purchase Frequency
- Seasons
- Locations

:contentReference[oaicite:3]{index=3}

---

# 🛠️ Tech Stack

### Programming

- Python
- SQL

### Database

- PostgreSQL

### Libraries

- Pandas
- NumPy
- SQLAlchemy
- Psycopg2

### Visualization

- Power BI

---

# 📂 Project Structure

```
Customer-Shopping-Behavior-Analysis/
│
├── data/
│   └── customer_shopping_behavior.csv
│
├── notebooks/
│   └── Customer_Shopping_Behavior_Analysis.ipynb
│
├── sql/
│   └── customer_behavior_sql_queries.sql
│
├── dashboard/
│   └── customer_dashboard.pbix
│
├── report/
│   ├── Business Problem Document.pdf
│   └── Customer Shopping Behavior Analysis.pdf
│
└── README.md
```

---

# ⚙️ Data Preparation (Python)

The dataset was cleaned and transformed using Python.

### Data Cleaning

- Loaded dataset using Pandas
- Checked data types
- Performed exploratory analysis
- Handled missing values
- Imputed missing Review Ratings
- Renamed columns using snake_case
- Created Age Groups
- Created Purchase Frequency features
- Removed redundant columns
- Loaded cleaned data into PostgreSQL

:contentReference[oaicite:4]{index=4}

---

# 🗄️ Database (PostgreSQL)

The cleaned dataset was imported into PostgreSQL using **SQLAlchemy** and **Pandas**.

```python
df.to_sql(
    "customer",
    engine,
    if_exists="replace",
    index=False
)
```

---

# 📈 SQL Business Analysis

The project answers important business questions using SQL.

### Analysis Performed

- Revenue by Gender
- High Spending Discount Users
- Top Rated Products
- Shipping Type Comparison
- Subscriber vs Non-Subscriber Analysis
- Discount Dependent Products
- Customer Segmentation
- Top Products per Category
- Repeat Buyers Analysis
- Revenue by Age Group

:contentReference[oaicite:5]{index=5}

---

# 📊 Power BI Dashboard

The interactive dashboard includes:

- Total Customers
- Average Purchase Amount
- Average Review Rating
- Revenue by Category
- Sales by Category
- Revenue by Age Group
- Sales by Age Group
- Subscription Analysis
- Interactive Filters

Dashboard filters:

- Gender
- Subscription Status
- Category
- Shipping Type

:contentReference[oaicite:6]{index=6}

---

# 💡 Business Recommendations

Based on the analysis:

- Increase subscription adoption through exclusive benefits.
- Reward repeat buyers with loyalty programs.
- Optimize discount strategies to protect margins.
- Promote highly rated and best-selling products.
- Focus marketing campaigns on high-revenue age groups and express-shipping users.

:contentReference[oaicite:7]{index=7}

---

# 🚀 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- PostgreSQL
- SQL Queries
- SQLAlchemy
- Data Modeling
- Business Intelligence
- Power BI Dashboard
- Data Visualization
- Business Analytics

---

# 📚 Tools Used

- Python
- Pandas
- PostgreSQL
- SQLAlchemy
- Psycopg2
- SQL
- Power BI
- VS Code
- Jupyter Notebook

---

# 📌 Future Improvements

- Build predictive customer segmentation models
- Customer Lifetime Value (CLV) prediction
- Churn prediction
- Sales forecasting
- Recommendation system
- Deploy interactive dashboard online

---

# 👨‍💻 Author

**Ankit Kumar**

B.Tech (Artificial Intelligence & Machine Learning)

Passionate about:

- Data Analytics
- Machine Learning
- Business Intelligence
- SQL
- Python
- Power BI

---

⭐ If you found this project useful, don't forget to **Star** the repository!
