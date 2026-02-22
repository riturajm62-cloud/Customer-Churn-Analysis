Customer Churn Analysis (End-to-End Data Analytics Project)

📊 Project Overview
This project focuses on identifying the root causes of customer churn for a telecommunication provider.By analyzing customer behaviour, contract types, and support interactions.I identified key "breaking points" where customers are more likely to leave and developed actionable strategies to improve reention.

🛠️ Tools & Technologies Used
1. Excel (Data Cleaning ,Pivot Tables, Dashboarding and Initial Analysis)
2. SQL (DuckDB in Jupyter Notebook)
3. Python (Data Handling)
4. Jupyter Notebook
5. GitHub (Project Documentation)

📁 Project Structure
1. data/ → Raw and cleaned datasets
2. excel/ → Excel data cleaning and analysis file
3. notebook/ → SQL analysis notebook

📌 Key Analysis Performed
1. Overall Churn Rate Analysis (KPI)
2. Churn by Contract Type
3. Churn by Customer Tenure
4. Churn by Monthly Charges
5. Churn by Internet Service Type

📈 Key Findings
1. Overall churn rate is approximately 34%, indicating a significant retention challenge.
2. Customers with month-to-month contracts show the highest churn risk.
3. New customers (0–1 year tenure) have the highest churn rate.
4. High monthly charge customers exhibit significantly higher churn.
5. Long-term customers show lower churn, indicating loyalty increases with tenure.
6. The "3-Call Breaking Point": Churn probability is stable until the 3rd support call, where it spikes to "58%", eventually reaching "100%" by the 8th call.
7. Contract Risk: Month-to-month subscribers churn at (43.2%), more than double the rate of annual subscribers (20.9%).
8. Payment Friction: Customers using manual payment methods (Electronic Checks) exhibit higher churn compared to those on Auto-pay.

💡 Business Recommendations
1. Introduce loyalty programs for new customers.
2. Encourage long-term contracts to reduce churn.
3. Review pricing strategy for high monthly charge customers.
4. Improve onboarding and early customer engagement.

📂 Dataset and Data Lifecycle

1. Data Cleaning
* Handled missing values in `support_calls` and `tenure`.
* Converted categorical `Churn` data into numerical `Churn_Value` (1/0) for statistical analysis.
* Currency Normalization: Stripped `$` and `,` symbols using Excel formulas and Find & Replace to ensure the data was SQL-ready.

2. Feature Engineering
* Created `Tenure_Group` categories to identify risk levels across different stages of the customer lifecycle.
* Calculated churn percentages across multiple dimensions using Pivot Tables.
* The dataset includes raw customer churn data and a cleaned version used for SQL and analytical modeling (Source Of raw data Kaggle.)
Dataset has more than 20,000 rows.
3. Visualization & Dashboarding
* Built an interactive dashboard featuring Slicers for dynamic filtering (e.g., by Payment Method).
* Created a Smoothed Line Chart to visualize the non-linear relationship between support calls and churn.
* Designed an "Insights Summary" sheet within Excel for stakeholder reporting.
<img width="1652" height="993" alt="Picture1" src="https://github.com/user-attachments/assets/86871c61-ff67-420f-ae9c-e47b05e98d1f" />

<img width="1653" height="993" alt="Picture2" src="https://github.com/user-attachments/assets/d5e3d20e-2f2f-4217-a7b6-b188fa29d0a2" />

👤 Author
Ritu Raj  
Aspiring Data Analyst | IIT Madras BS in Data Science (Foundation)
