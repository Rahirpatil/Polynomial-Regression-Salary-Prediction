# 📈 Polynomial Regression – Salary Prediction

This project demonstrates how to use **Polynomial Regression** to model and predict salary based on position level using a non-linear curve fitting approach.

---

## 📁 Dataset Overview

- File: `Position_salaries.xlsx.csv`
- Columns:
  - `Position`
  - `Level` (Independent Variable)
  - `Salary` (Target)

---

## 📌 Project Workflow

1. **Import Libraries**
   - Imported `pandas`, `numpy`, `matplotlib.pyplot`, and `sklearn`.

2. **Load Dataset**
   - Loaded and explored data with `.head()` and `.columns`.

3. **Split Data**
   - X = `Level`  
   - y = `Salary`

4. **Model Training**
   - Fitted both **Linear Regression** and **Polynomial Regression** models.
   - Transformed X to polynomial features using `PolynomialFeatures`.

5. **Prediction**
   - Predicted salary for a specific input level (e.g., 6.5).

6. **Visualization**
   - Plotted:
     - Original data points
     - Linear Regression line
     - Polynomial Regression curve (higher-degree fit)

---

## 🛠️ Technologies Used

- Python 3.x
- Libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `sklearn.linear_model`
  - `sklearn.preprocessing`

