# Retail Customer Behavior Analytics

## 📌 Project Overview

This project provides an end-to-end analysis of customer shopping behavior. The goal was to transform raw retail data into actionable insights by identifying purchasing patterns, discount effectiveness, and customer segmentation. The project spans the entire data lifecycle: **Data Cleaning (Python), Deep-Dive Analysis (SQL), and Interactive Visualization (Power BI).**

## 📊 Dataset

* **Source:** [Link to dataset or name, e.g., Kaggle / Internal CSV]
* **Description:** Contains over [Number] records of customer transactions, including demographics, purchase history, item categories, and promotional data.
* **Key Columns:** `Customer_ID`, `Age`, `Item_Purchased`, `Purchase_Amount`, `Discount_Applied`, and `Previous_Purchases`.

## 🛠️ Tech Stack

* **Data Processing:** Python (Pandas, NumPy)
* **Database:** SQL Server (T-SQL)
* **Visualization:** Power BI
* **Reporting:** Gamma (AI-powered presentation), Microsoft PowerPoint

## 🚀 Project Steps

### 1. Data Cleaning & EDA (Python)

* Handled missing values and standardized categorical strings.
* Performed Exploratory Data Analysis (EDA) to detect outliers in purchase amounts.
* Exported cleaned data to `.csv` for database ingestion.

### 2. Database Management & Analysis (SQL)

* Imported cleaned datasets into **SQL Server**.
* Wrote complex queries to calculate:
* **Discount Success Rate:** Analyzing which items sold best with promotions.
* **Retention Metrics:** Segmenting customers based on frequency of purchase.
* **Category Performance:** Identifying high-value inventory items.



### 3. Data Visualization (Power BI)

* Built a dynamic dashboard connecting directly to the SQL database.
* Key visuals include:
* **Sales Heatmap:** Regional distribution of purchases.
* **KPI Cards:** Total Revenue, Average Order Value, and Discount Impact.
* **Slicers:** Interactive filtering by Category and Season.



## 📈 Key Results

* **Insight 1:** Identified that "Backpacks" and "Clothing" categories have a 100% discount application rate, suggesting a need for pricing strategy review.
* **Insight 2:** Customers in the 25-35 age bracket contribute to 40% of total revenue.
* **Insight 3:** [Add one more specific finding from your data].

## 💻 How to Run

1. **Clone the Repo:** `git clone https://github.com/yourusername/project-name.git`
2. **Python Setup:** Run `pip install pandas matplotlib` and execute `cleaning_script.py`.
3. **SQL Setup:** Run the scripts in the `/sql` folder to create tables and views.
4. **Power BI:** Open the `.pbix` file to view the interactive dashboard.

---

Would you like me to help you draft the "Executive Summary" slide content for your Gamma presentation?

[Example: Best-selling products and categories]

[Example: Seasonal sales patterns]

[Example: Customer segments with highest engagement]
