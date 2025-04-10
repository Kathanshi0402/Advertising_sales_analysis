# 📈 Advertising Sales Analysis with Linear Regression

This project investigates the impact of advertising budgets across different media (TV, Radio, Newspaper) on product sales. Using **linear regression modeling**, we assess how each medium influences sales and validate statistical assumptions to ensure model reliability.

---

## 📊 Overview

- **Objective:** Understand how advertising spend across various channels affects sales and build a predictive model.
- **Data:** Classic advertising dataset with spending on TV, Radio, and Newspaper vs. Sales.
- **Tools:** Python, pandas, statsmodels, seaborn, matplotlib

---

## 🧠 Key Components

### 1. Exploratory Data Analysis (EDA)
- Visualized relationships between advertising media and sales
- Correlation analysis to understand linear relationships

### 2. Model Building
- Implemented **Simple and Multiple Linear Regression**
- Analyzed coefficients to interpret media impact

### 3. Assumption Testing
- Checked:
  - **Linearity** (scatter plots, correlation)
  - **Homoscedasticity** (residual plots)
  - **Independence of errors** (Durbin-Watson test)
  - **Normality of residuals** (Q-Q plot, histogram)
  - **Multicollinearity** (VIF scores)
  - **Zero mean of residuals**

### 4. Model Evaluation
- Compared models using adjusted R², F-statistic, and AIC
- Discussed model limitations and potential improvements


---

## 📌 Results Summary

- TV and Radio advertising significantly affect sales, while Newspaper has minimal impact.
- The multiple linear regression model achieved high R² and passed all key statistical assumptions.
- Verified model interpretability and robustness through residual diagnostics.

---

## 🛠️ Tools Used

- **Python**
- **pandas**, **numpy**, **matplotlib**, **seaborn**
- **statsmodels** for regression and diagnostics

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Kathanshi0402/Advertising_sales_analysis.git
