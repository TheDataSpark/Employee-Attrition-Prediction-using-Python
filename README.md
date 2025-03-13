# Overview
This project focuses on predicting employee attrition using machine learning techniques. The goal is to identify employees at risk of leaving the organization by analyzing factors such as job satisfaction, workload, tenure, and promotions. The model aims to provide actionable insights to HR teams, enabling them to proactively address retention challenges.

## Key Features
- Predictive Modeling: Built and optimized machine learning models (Random Forest, XGBoost) to predict employee attrition with an AUC score of 0.85.
- Exploratory Data Analysis (EDA): Conducted in-depth analysis to uncover trends, such as employees with low satisfaction levels (< 0.45) and high workloads (> 250 hours/month) being 3x more likely to leave.
- Feature Engineering: Created new features like workload ratio and tenure squared, improving model performance by 8%.
- Hyperparameter Tuning: Utilized RandomizedSearchCV to optimize model hyperparameters, reducing training time by 30%.
- Actionable Insights: Identified key drivers of attrition, such as employees with < 4 projects and no promotions in the last 5 years, enabling targeted retention strategies.

## Dataset
The dataset includes the following features:
- satisfaction_level: Employee satisfaction score (0-1).
- last_evaluation: Performance evaluation score (0-1).
- number_project: Number of projects the employee is involved in.
- average_montly_hours: Average monthly hours worked.
- time_spend_company: Tenure in years.
- Work_accident: Whether the employee had a work accident (1 = Yes, 0 = No).
- left: Target variable indicating if the employee left (1 = Yes, 0 = No).
- promotion_last_5years: Whether the employee was promoted in the last 5 years (1 = Yes, 0 = No).
- sales: Department the employee belongs to.
- salary: Salary category (low, medium, high).

## Results
- Achieved an AUC score of 0.85, exceeding the target of 0.84.
- Identified that employees with low satisfaction levels and high workloads are 3x more likely to leave.
- Provided actionable insights to reduce attrition risk by 15%.

## Tools & Technologies
- Programming Language: Python
- Libraries: Scikit-learn, XGBoost, Pandas, NumPy, Matplotlib, Seaborn
- Techniques: Feature Engineering, Hyperparameter Tuning, Cross-Validation, Ensemble Learning
