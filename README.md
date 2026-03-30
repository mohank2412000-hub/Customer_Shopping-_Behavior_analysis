# Customer_Shopping-_Behavior_analysis
Data analytics Project Customer Shopping Behavior analysis Using Python, SQL, and Power Bi

# 📊 Data Analytics Project

## 🔍 Overview

This project demonstrates an end-to-end **data analytics workflow** using Python, SQL, and Power BI. The goal is to extract meaningful insights from raw data by performing data cleaning, exploratory data analysis (EDA), database querying, and visualization.

The project simulates a real-world business scenario where data is transformed into actionable insights for decision-making.

---

## 📁 Dataset

* Source: CSV dataset (Customer Shopping Behavior)
* Records: ~3900 rows
* Features include:

  * Customer demographics (Age, Gender)
  * Product details (Category, Item Purchased)
  * Transaction data (Purchase Amount, Season)
  * Customer behavior (Subscription, Frequency, Discount, Rating)

---

## 🛠 Tools & Technologies

* **Python** (Pandas, NumPy, Seaborn, Matplotlib)
* **SQL** (PostgreSQL / MySQL / SQL Server)
* **Power BI** (Dashboard & Visualization)
* **Gamma** (Presentation creation)
* **Jupyter Notebook / Anaconda**

---

## ⚙️ Project Steps

### 1. Data Loading

* Imported dataset using Pandas
* Inspected structure using `.head()`, `.info()`, `.describe()`

### 2. Data Cleaning

* Removed duplicates and null values
* Converted categorical data into usable formats
* Dropped irrelevant columns
* Created new features (e.g., purchase frequency in days)

### 3. Exploratory Data Analysis (EDA)

* Analyzed:

  * Sales by category
  * Customer demographics
  * Discount impact on sales
* Used visualizations (bar charts, histograms, scatter plots)

### 4. SQL Analysis

* Loaded cleaned data into database
* Performed queries such as:

  * Total revenue by category
  * Customer segmentation
  * Top-performing products
  * Discount impact analysis
* Used advanced SQL:

  * `GROUP BY`, `CASE WHEN`
  * Window functions (`ROW_NUMBER`, `RANK`)
  * CTEs (`WITH` clause)

### 5. Power BI Dashboard

* Built an interactive dashboard including:

  * KPI cards (Revenue, Customers, Avg Spend)
  * Sales by category
  * Customer segmentation
  * Seasonal trends
  * Top products

### 6. Report & Presentation

* Created a detailed analytical report
* Designed a presentation using Gamma covering:

  * Problem statement
  * Analysis process
  * Key insights
  * Business recommendations

---

## 📊 Dashboard Highlights

* Total Revenue and Customer Overview
* Category-wise Sales Performance
* Customer Behavior Analysis
* Discount vs Profit Insights
* Seasonal Trends

---

## 📈 Key Results

* Identified top-performing product categories
* Analyzed customer purchasing patterns
* Found impact of discounts on sales
* Discovered high-value customer segments
* Generated actionable business insights

---

## ▶️ How to Run

### 1. Clone the Repository

```bash
git clone <your-repo-link>
cd data-analytics-project
```

### 2. Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn sqlalchemy pymysql
```

### 3. Run Python Analysis

* Open Jupyter Notebook
* Execute all cells for data cleaning and EDA

### 4. Connect to SQL

* Create database in PostgreSQL/MySQL/SQL Server
* Upload cleaned dataset using Python (`to_sql()`)

### 5. Open Power BI

* Connect to database or CSV
* Load dataset and view dashboard

---

## 💡 Conclusion

This project demonstrates a complete **data analytics pipeline**, from raw data processing to business insights and visualization. It highlights practical skills required for a **Data Analyst role**, including Python, SQL, and dashboarding.

---

## 📌 Author

**Mohan K**
Aspiring Data Analyst
