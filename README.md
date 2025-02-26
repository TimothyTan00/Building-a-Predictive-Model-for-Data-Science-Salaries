# Analyzing Key Determinants of Data Science Salaries and Building a Predictive Model

## Overview
This project analyzes key determinants of salaries in data science roles and builds a predictive model to estimate salary levels based on influential factors. Using a dataset from AIJobs.net (2020-2024) with over 60,000 records, we explore how experience level, remote work, geographic location, and company size impact compensation. Our goal is to provide valuable insights for job seekers and employers while developing an interpretable machine learning model for salary prediction.

## Methodology
### 1. Data Cleaning and Preprocessing
* Handled duplicates, outliers, and inconsistencies.
* Grouped job titles into broader categories and categorized locations.
* Encoded ordinal categorical variables for meaningful comparisons.
### 2. Exploratory Data Analysis
* Visualized data distributions using histograms and bar plots.
* Conducted bivariate analysis to explore relationships between salary and key factors.
* Used correlation analysis to address collinearity, removing redundant features.
### 3. Feature Selection and Modeling
* Applied Chi-Squared tests, Lasso Regression, and Random Forest feature importance analysis.
* Tested multiple regression models: Multiple Linear Regression, Lasso, Support Vector Regression (SVR), K-Nearest Neighbors (KNN), Random Forest, and XGBoost.
* Evaluated models based on R² score and Root Mean Squared Error (RMSE), with XGBoost performing best.

## Key Findings
* **Experience Level** is the strongest predictor of salary, highlighting the importance of industry experience.
* **Remote work** positively influences salaries, with fully remote roles often commanding higher pay.
* **Company size** impacts compensation, with smaller companies generally offering lower salaries.
* **High-salary roles** are harder to predict accurately due to variability and limited data in this range.

## References
Yosifova, A. (2024). "Data science salaries around the world in 2024." 365 Data Science.

Quan, T. Z., & Raheem, M. (2022). "Salary prediction in data science field using specialized skills and job benefits." Journal of Applied Technology and Innovation.

Voleti, R., & Jana, B. (2021). "Predictive analysis of HR salary using machine learning techniques." International Journal of Engineering Research & Technology.
