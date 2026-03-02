# 📊 Financial Performance Analysis Dashboard — Power BI

## 📌 Project Overview

The **Financial Performance Analysis Dashboard** is an interactive Power BI report designed to monitor, analyze, and visualize financial data across categories, accounts, and time periods.
It provides a comprehensive overview of spending behavior, income trends, and account distribution to support financial decision-making.

---

## 🎯 Key Insights Provided

* Compare **monthly income vs expenses**
* Identify **highest spending categories**
* Analyze **sub-category level expenses**
* Track **daily transaction trends**
* Monitor **account type usage distribution**
* Evaluate **quarterly financial performance**

---

## 📊 Dashboard Components

### 🔢 KPI Summary Cards

* Bills → 37K
* Food → 34K
* Living → 36K
* Travel → 33K

These cards highlight major expense segments at a glance.

---

### 📈 Visualizations Used

* **Bar Chart:** Expense by Category
* **Pie Chart:** Debit by Company
* **Horizontal Bar Chart:** Expense by Sub-Category
* **Clustered Bar Chart:** Monthly Income vs Expense
* **Donut Chart:** Debit by Account Type
* **Line Chart:** Daily Transaction Trend
* **Comparison Chart:** Total Income vs Total Expense

---

### 🎛 Interactive Filters (Slicers)

Users can dynamically filter the dashboard by:

* Company
* Account
* Quarter (Q1–Q4)

All visuals update automatically based on selection.

---

## 🧠 DAX Measures Used

```DAX
Total Debit = SUM(Finance[Debit])
Total Credit = SUM(Finance[Credit])

Total Expense =
CALCULATE([Total Debit], Finance[Category Type] = "Expense")

Total Income =
CALCULATE([Total Credit], Finance[Category Type] = "Income")

Balance = [Total Income] - [Total Expense]
```

---

## 📈 Business Value

This dashboard helps users:

* Monitor financial health
* Detect high-expense areas
* Compare account usage
* Track spending patterns
* Support budgeting decisions
* Identify financial trends quickly

---

## 🎨 Design Features

* Professional financial theme layout
* High-contrast color palette for clarity
* Structured grid alignment
* Category-wise segmentation
* Visual storytelling design

---
 → Dataset source

---

## 🚀 How to Use

1. Download repository files
2. Open `.pbix` file in Power BI Desktop
3. Refresh data if needed
4. Use filters to explore insights

---

## 👩‍💻 Author

**Harini B**

---

⭐ *If you found this project useful, consider giving it a star!*

