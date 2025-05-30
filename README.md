# 🕵️ Expense Report Anomaly Detection

This project applies anomaly detection techniques to real-world expense report data, with the goal of identifying suspicious or fraudulent expense entries. It is designed as a portfolio project to demonstrate data analysis, preprocessing, SQL querying, and machine learning skills.

## 📊 Dataset

**Sources**: Provided CSV of 510 expense entries
**Fields**:
- `Employee_ID`
- `Date`
- `Expense_Amount`
- `Location`
- `Department`

## 🎯 Objective

Detect anomalies in expense reports to flag potentially fraudulent or irregular transactions that deviate from typical employee behavior, department norms, or organizational averages.

## 🧰 Tools & Technologies

- **Python** (pandas, numpy, scikit-learn,matplotlib, seaborn)
- **SQLite** (via DBeaver for SQL querying)
- **Jupyter Notebooks**
- **GitHub** (version control & portfolio)
- **Optional**: Tableau or Power BI for visualization

## 📈 Methodology

1. **EDA & Preprocessing**
   - Explore patterns by department, expense type, and location

    Convert data types, engineer features (day, week, etc.)
   - Normalize/standardize amounts

2. **Anomaly Detection Approaches**
   - **Z-Score**: Flag values > 3 standard deviations
   - **Isolation Forest**: Tree-based unsupervised algorithm
   - Optional: Autoencoder for deep learning approach

3. **SQL Exploration**
   - Run descriptive queries in DBeaver on the SQLite dataset
   - Aggregate spending by employee, department, category

4. **Visualizations**
   - Distribution plots of expenses
   - Boxplots by department/category
   - Highlighted anomalies

## 💼 For Contra or Portfolio Use

This project is built to:
- Demonstrate end-to-end data analysis skills
- Highlight anomaly detection for business applications
- Present clean, modular, and reproducible code