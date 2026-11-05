Day 17 – Customer Churn Driver Analysis
Internship: Veda Technology – Data Analytics Internship
Objective
Analyze customer churn patterns in the Telco Customer Churn dataset and identify customer segments with higher observed churn rates.
Dataset
- 7,043 customer records and 21 columns
- Target variable: Churn
- Fields analyzed: tenure, Contract, InternetService, PaymentMethod, OnlineSecurity, and TechSupport
Tools
Python, Pandas, NumPy, Matplotlib, Seaborn and Jupyter Notebook.
Workflow
1. Loaded the CSV dataset into Pandas.
2. Inspected dimensions, data types, missing values and duplicates.
3. Converted TotalCharges to numeric.
4. Replaced the 11 blank TotalCharges values revealed during conversion with 0.
5. Calculated overall churn and segment-level churn rates.
6. Created visualizations and exported the cleaned dataset.
Overall Results
Metric	Result
Total customers	7,043
Churned customers	1,869
Retained customers	5,174
Overall churn rate	26.54%


Segment Findings
Category	Segment	Churn rate
Tenure	0–12 months	47.68%
Tenure	13–24 months	28.71%
Tenure	25–48 months	20.39%
Tenure	49–72 months	9.51%
Contract	Month-to-month	42.71%
Contract	One year	11.27%
Contract	Two year	2.83%
Internet service	Fiber optic	41.89%
Payment method	Electronic check	45.29%
Online Security	No	41.77%
Tech Support	No	41.64%


Business Recommendations
- Improve onboarding and engagement during the first year.
- Investigate billing experience among electronic-check users.
- Explore suitable retention offers for month-to-month customers.
- Review fiber-optic service quality, installation and value perception.
- Improve awareness of Online Security and Tech Support.
Interpretation Note
These are descriptive associations, not proof of causation. Customer segments overlap, and the analysis does not control for other variables. Further statistical analysis or a validated predictive model is needed before making causal claims.
Files
- Day17_Churn_Driver_Analysis.ipynb – analysis notebook
- Cleaned_Telco_Churn.csv – cleaned dataset
- Day17_Churn_Driver_Analysis_Report.docx – project report
