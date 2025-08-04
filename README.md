
# 🎬 Movie Revenue Prediction in R

This R Markdown project analyzes the factors influencing U.S. box office revenue of 44 movies using regression modeling. It includes exploratory data analysis, model selection, and performance interpretation — all structured in a clean reproducible format.

---

## 🔧 Tools & Libraries

- `dplyr`, `ggplot2` for data wrangling and visualization
- `readxl` for Excel file import
- `car` for multicollinearity checks (VIF)
- Base R for regression modeling and diagnostics

---

## ✅ Key Activities

### 1. Data Preparation
- Imported `.xls` movie dataset
- Converted categorical variables (`Genre`, `Rating`, `Sequel`) to factors
- Identified and handled outliers and missing data

### 2. Exploratory Data Analysis
- Boxplots for `Budget`, `Opening`, `USRevenue`, etc.
- Noted high-revenue outliers in Opening and U.S. Revenue
- Initial scatter plots and correlation insights

### 3. Model Building
- Fitted various linear models
- Introduced quadratic and interaction terms
- Used p-values and R² for evaluation

### 4. Model Selection
- Applied backward elimination and purposeful selection
- Final model: `USRevenue ~ Opening + Review`

### 5. Model Diagnostics
- Residual analysis to check assumptions
- Confidence Intervals and prediction intervals
- Multicollinearity via Variance Inflation Factor (VIF)

---

## 📈 Outcome

A statistically robust regression model predicting U.S. revenue based on opening earnings and critic reviews, useful for understanding box office dynamics and building predictive systems.

---

## 📁 File

- `Project_4810_Movie_REAL_Finali.Rmd`: Full analysis with code, outputs, and interpretations

---
