# HR_Attrition_DS_Project
HR Attrition Data Science Project
Problem definition
-------------------
In this project we focus on employees who willingly leave their jobs. We aim to predict when and which employees will be likely to resign. This allows the HR department to focus their efforts when improving retention plans and employee satisfaction. To build a model, we plan to use an HR dataset found in the Kaggle repository. The dataset consists of about 15,000 records. The target variable is employee churn, whether the employee left the company or not. The features in the data set are the following. 
•	satisfaction_level: Employee reported satisfaction between 0 and 1.
•	last_evaluation: Supervisor rated performance between 0 and 1.
•	number_projects: The number of projects assigned to an employee.
•	average_monthly_hours: The number of hours worked in a month by an employee on average.
•	time_spent_company: The number of years spent at the company.
•	work_accident: Whether the employee experienced a work accident (0 for No, 1 for Yes) 
•	promotion_last_5years: Whether the employee was promoted in the last five years (0 for No, 1 for Yes).
•	Departments: Which department the employee belongs to (Sales, technical, support, hr etc.)
•	Salary: Salary level categorized as low, medium or high.

Approach
----------
We intend to use a supervised learning, classification model to predict whether an employee will leave the company. We intend to test the accuracy, precision and recall of different classification algorithms, before using the XGBoost Machine Learning approach for robustness, best accuracy, speed and performance,  following the approach of others have in the literature. We intend to compare XGBoost to Stacking and assess the performance of both approaches.
The target variable is imbalanced in the dataset with a ratio 80:20 of ‘stayed’ to ‘left’. Therefore, we intend to use both oversampling and no sampling methods in order to gauge the differences on the predicted results. 

