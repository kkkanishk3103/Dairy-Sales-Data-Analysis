# 🐄 Dairy Sales Data Analysis


## 📌 Project Overview

This integrated project focuses on analyzing the dairy sector using Python programming, statistical methods, and machine learning techniques. The aim is to explore production trends, financial performance, customer behavior, and predictive modeling for sales channels. The study offers insights for optimizing decision-making and ensuring sustainability in the dairy industry.

## 📁 Folder Structure

Dairy Sales Data Analysis/
├── Python code/
│ └── dairy_dataset.ipynb
│
├── Sheets/
│ ├── Data/
│ │ └── dairy_dataset.csv
│ │
│ └── Output/
│ ├── contingency_table_Dairysales.csv
│ ├── expected_df_Dairysales.csv
│ ├── monthly_gross_profit.csv
│ ├── simple_random_sample_dairy.csv
│ ├── stratified_sample_dairy.csv
│ └── systematic_sample_dairy.csv
│
├── Report/
│ └── Dairy_sales Analysis Report.pdf
│
└── README.md

---

## 🛠️ Tools & Technologies Used

- **Python** (Jupyter Notebook)
  - `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`, `scipy`, `statsmodels`
- **Excel / CSV**
- **Statistical Techniques**: ANOVA, Chi-Square, Sampling
- **Machine Learning**: Decision Tree Classification
- **Time Series Analysis**: Trend forecasting using Linear Regression, Moving Average, Semi-Average

---

## 🧪 Methodology

### 1. **Data Cleaning & Preprocessing**
- Handled missing values, duplicates, and incorrect date formats.
- Detected and removed outliers using IQR method.

### 2. **Sampling Techniques**
- Applied Simple Random, Systematic, and Stratified Sampling.
- Stratified sampling (by Product Name) showed lowest variance and was selected as the best method.

### 3. **Inferential Statistics**
- One-way ANOVA tested if average Price per Unit differed by Sales Channel.
- Result: p-value > 0.05 → No significant difference found.

### 4. **Time Series Analysis**
- Analyzed monthly revenue trends using:
  - Least Squares Method
  - Moving Average
  - Semi-Average
- Forecasted next 12 months revenue and visualized trend direction.

### 5. **Financial Data Analysis**
- Monthly gross profit was calculated and plotted.
- Identified peak and low-profit periods to guide pricing and cost strategies.

### 6. **Count & Categorical Data Analysis**
- Performed Chi-Square Test to examine relationship between Brand and Customer Location.
- Result: p-value < 0.05 → Significant relationship exists.

### 7. **Machine Learning**
- Trained a **Decision Tree Classifier** to predict `Sales Channel` based on other features.
- Achieved good accuracy; visualized feature importance to guide decisions.

---

## ▶️ How to Run

1. Open the notebook:
Python code/dairy_dataset.ipynb
2. Run each cell in the notebook to view the analysis, results, and visualizations.

---

## 📈 Output Files

The following CSVs are generated during the analysis:
simple_random_sample_dairy.csv
stratified_sample_dairy.csv
systematic_sample_dairy.csv
contingency_table_Dairysales.csv
expected_df_Dairysales.csv
monthly_gross_profit.csv

---

They can be found in:
📂 Sheets/Output/

---

## 📄 Report

The full documentation of the project is available here:
📄 Report/Dairy_sales Analysis Report.pdf

Includes:
Industry Overview
Project Objectives & Scope
Step-by-step Analysis
Tables, Graphs, and Results
Conclusion & References

---

## 🙋‍♂️ Author

Kanishk Mehta
Email - kanishkmehta100@gmail.com
Github - kkkanishk3103
Linkedin - www.linkedin.com/in/kanishk-mehta-b473272a3

---
