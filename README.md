# Employee-Attrition-Prediction-Using-Machine-Learning
This project analyzes employee attrition patterns and develops a machine learning model to predict whether an employee is likely to leave the company.
## Business Problem
Employee turnover increases recruitment costs and impacts productivity. By predicting attrition risk, organizations can proactively implement retention strategies.
## Dataset

IBM HR Analytics Employee Attrition Dataset

## Key Questions


- Which departments experience the highest attrition rates?
- Does overtime increase the likelihood of employee attrition?
- How does monthly income impact employee retention?
- Which age groups are most likely to leave the company?
- Can machine learning accurately predict employee attrition?
## Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Machine Learning
- Random Forest Classification
- Model Evaluation
- Power BI Dashboarding
- Business Analysis
## Machine Learning Model

**Algorithm Used:** Random Forest Classifier
### Evaluation Metrics
- Accuracy: 86.73%
- Precision: 50.00%
- Recall: 10.26%
- F1 Score: 17.02%
## Top Factors Influencing Employee Attrition

Using the Random Forest Classifier, feature importance analysis was performed to identify the variables that had the greatest impact on predicting employee attrition.

| Rank | Feature | Importance Score |
|--------|----------|----------|
| 1 | MonthlyIncome | 7.50% |
| 2 | OverTime | 6.48% |
| 3 | Age | 5.69% |
| 4 | DailyRate | 5.05% |
| 5 | TotalWorkingYears | 4.81% |
| 6 | MonthlyRate | 4.71% |
| 7 | EmployeeNumber | 4.53% |
| 8 | HourlyRate | 4.34% |
| 9 | DistanceFromHome | 4.20% |
| 10 | YearsAtCompany | 4.19% |
## Dashboard Features

- Attrition by Department
- Attrition by Job Role
- Attrition by Age Group
- Attrition by Income Group
- Employee Risk Distribution
- High-Risk Employee Analysis

#Dasboard Overview
<img width="1340" height="850" alt="Screenshot 2026-06-03 224920" src="https://github.com/user-attachments/assets/fb7b40ac-e8f6-4cc7-b29c-2bfa88695f63" />

<img width="1328" height="803" alt="Screenshot 2026-06-03 225240" src="https://github.com/user-attachments/assets/30fdf422-9a21-443e-beb5-41b5527c3976" />

### Key Findings

- Monthly Income was the strongest predictor of employee attrition.
- Employees working overtime were significantly more likely to leave the company.
- Age and total working experience were important factors in predicting turnover.
- Employees living farther from work showed a slightly higher attrition risk.
- Tenure-related variables such as Years At Company and Total Working Years contributed to prediction accuracy.

### Business Recommendation
- Improve employee engagement programs.
- Review compensation structures.
- Focus retention strategies on high-risk employee groups.
