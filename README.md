
# 📊 Finance Dashboard — Power BI Project

## 📌 Project Overview

This project is an interactive **Finance Dashboard built in Power BI** designed to analyze income, expenses, account performance, and spending trends.
The dashboard enables users to monitor financial activity, identify spending patterns, and make data-driven decisions.

---

## 🎯 Objectives

* Track total income, expenses, and balance
* Analyze spending by category
* Compare financial activity across accounts
* Monitor monthly financial trends
* Provide interactive filtering for detailed insights

---

## 🧰 Tools & Technologies Used

* Power BI Desktop
* DAX (Data Analysis Expressions)
* Power Query
* Excel Dataset

---

## 📂 Dataset

**File:** `Finance_Expenses.xlsx`
Contains financial transaction data with the following columns:

| Column        | Description             |
| ------------- | ----------------------- |
| Date          | Transaction date        |
| Account       | Account used            |
| Category      | Expense/Income category |
| Category Type | Income or Expense       |
| Amount        | Transaction value       |

---

## 📊 Dashboard Features

✔ KPI Cards — Total Income, Expense, Balance
✔ Donut Chart — Expense Distribution
✔ Bar Chart — Account Analysis
✔ Column Chart — Monthly Trend
✔ Interactive Filters — Date, Account, Category
✔ Dynamic Visual Interactions

---

## 🧠 DAX Measures Used

**Total Income**

```DAX
Total Income =
CALCULATE(SUM(Data[Amount]), Data[Category Type] = "Income")
```

**Total Expense**

```DAX
Total Expense =
CALCULATE(SUM(Data[Amount]), Data[Category Type] = "Expense")
```

**Balance**

```DAX
Balance = [Total Income] + [Total Expense]
```

---

## 📸 Dashboard Preview

*(Add screenshot here after uploading image)*

---

## 🚀 How to Use

1. Download `.pbix` file from repository
2. Open using **Power BI Desktop**
3. Refresh data if needed
4. Use slicers to interact with dashboard

---

## 📈 Business Value

This dashboard helps stakeholders:

* Monitor financial health
* Detect overspending areas
* Compare account performance
* Support budgeting decisions

---

## 📎 File Included

* `finance dashboard.pbix` → Main dashboard file

---

## 👩‍💻 Author

**Harini B**

---

## ⭐ If you like this project

Give it a ⭐ on GitHub and feel free to fork!

---
