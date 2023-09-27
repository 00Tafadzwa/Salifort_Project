# Employee Attrition Prediction at Salifort Motors

## Key Findings

### Data Preparation and Initial Observations
- **Scaling for Usability:** Scaling is necessary to accommodate variations in the "average_monthly_hours" feature.
- **Project Handling:** The maximum number of projects an employee handled is seven.
- **Salary Distribution:** The "low" salary category is the most common among employees.
- **Department Insights:** The sales department has the highest number of employees.

### Relationships Between Variables
- **Satisfaction and Tenure:** Negative correlation between "Satisfaction_level" and "time_spend_company."
- **Workload and Tenure:** The "work_load" feature negatively correlates with "time_spend_company."
- **Early Turnover Indicator:** High workload in the first 3 years relates to more employee turnover.

### Data Distributions
- **Skewed Data:** Data distributions are not normal, indicating skewness.

### Data Transformations
- **Feature Engineering:** "work_load" feature created to proxy workload.
- **Enhanced Clarity:** Improved clarity for "Number_project" and "average_monthly_hours."

### Workload and Time Spent at Company
- **Efficiency Trend:** Scatter plot shows a gradual decline in workload as employees spend more time with the company.

### Early Employee Turnover
- **Critical Period:** A significant number of employees leave within the first 3 years of tenure.
- **Potential Factors:** Possible factors include high workload for newcomers.

### Logistic Regression Results
- **Model Accuracy:** 80.75%
- **Precision Score:** 67.87%
- **Recall Score:** 68.49%
- **Key Features:** satisfaction_level, last_evaluation, number_project, average_monthly_hours, time_spend_company, work_accident, promotion_last_5years, salary, work_load, department_...

### Decision Tree Model Results
- **Impressive Performance:** Impressive F1 score: 94.35%
- **Accuracy:** High accuracy: 97.27%
- **Precision:** Precise predictions with a score of 98.10%
- **Recall:** Strong recall: 92.74%
- **Minimal False Negatives:** Minimal false negatives, indicating the model's reliability.
- **Top Factors:** Key factors for analysis include satisfaction level, time spent at the company, workload, last evaluation, number of projects, and average monthly hours.

These key findings provide valuable insights into employee attrition and the performance of predictive models. They inform strategies to improve employee retention and guide decision-making at Salifort Motors.
