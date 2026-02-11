# 🛒 Superstore Sales Analysis using Python

## 📌 Project Overview

This project focuses on analyzing a Superstore Sales dataset containing approximately **51,291 rows** of transactional data.  

The analysis was performed using **Python in Jupyter Notebook** to uncover key business insights related to sales performance, profitability, regions, product categories, shipping modes, and seasonal trends.

---

## 🎯 Project Objective

The main objective of this project is to:

- Analyze overall sales and profit performance
- Identify high-performing product categories
- Evaluate regional sales distribution
- Understand shipping mode return patterns
- Test business hypotheses using data analysis
- Generate actionable business insights

---

## 💼 Business Problem Statement

The Superstore operates across multiple regions and product categories. The management wants to understand:

- Which product categories generate the highest profit?
- Which region has the highest sales?
- Are sales higher during certain months?
- Do weekdays generate more profit than weekends?
- Which shipping mode has the lowest return rate?

The goal is to analyze the data and provide insights that help improve revenue and profitability.

---

## 📊 Dataset Information

- Dataset Name: Superstore Sales Dataset
- Total Rows: **51,291**
- Contains transactional sales data
- Includes features such as:
  - Order Date
  - Ship Date
  - Region
  - Category
  - Sub-Category
  - Sales
  - Profit
  - Shipping Mode
  - Customer Segment
  - Returned Orders

---

## 🔄 Project Workflow

### 1️⃣ Importing Required Libraries

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

---

### 2️⃣ Data Gathering

- Loaded dataset using `pd.read_csv()`
- Handled encoding issues using `encoding='latin1'`

---

### 3️⃣ Data Understanding

Performed initial data exploration:

- Checked first 5 rows using `head()`
- Checked last 5 rows using `tail()`
- Checked dataset shape (rows and columns)
- Used `info()` to get:
  - Data types
  - Non-null counts
- Checked for missing values
- Checked for duplicate records
- Generated statistical summary using `describe()`

---

### 4️⃣ Data Cleaning

- Removed duplicate records
- Checked and handled null values
- Dropped unnecessary columns
- Ensured correct data types
- Verified data consistency

---

### 5️⃣ Hypothesis Testing

The following business hypotheses were tested:

#### 🔹 Hypothesis 1  
Technology products have the highest profit margin compared to other categories.

#### 🔹 Hypothesis 2  
The East region has the highest sales compared to other regions.

#### 🔹 Hypothesis 3  
Sales are higher during certain months of the year.

#### 🔹 Hypothesis 4  
Orders with same-day shipping have the lowest rate of returned products.

#### 🔹 Hypothesis 5  
Company profit is higher on weekdays compared to weekends.

Each hypothesis was validated using:

- `groupby()` operations
- Aggregations (sum, mean, count)
- Percentage calculations
- Data visualization (bar charts, line plots)

---

## 📈 Key Business Insights

- ✅ Technology category generated the highest profit margin.
- ✅ Central region recorded the highest overall sales.
- ✅ Sales showed seasonal trends during certain months.
- ✅ Same-day shipping did not always have the lowest return rate.
- ✅ Weekday profits were generally higher than weekend profits.
- ✅ Office Supplies and Technology significantly contribute to total profit.

---

## 🛠 Tools & Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Git & GitHub

---

## 💡 Business Outcomes

This analysis helps stakeholders:

- Identify profitable product categories
- Focus on high-performing regions
- Optimize shipping strategies
- Improve sales during low-performing months
- Support data-driven business decisions

---

## ✅ Conclusion

The Superstore Sales Analysis project demonstrates how structured data cleaning, exploratory data analysis, and hypothesis testing can generate meaningful business insights.

By analyzing 51,291 rows of sales data, key trends in profitability, regional performance, shipping behavior, and seasonal sales were identified, enabling better strategic decision-making.

---

## 👩‍💻 Author

**Nandini**  
Python | SQL | Data Analysis | Excel | Power BI

