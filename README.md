# Telecom_Churn_Customers---project
Built a machine learning model to predict customer churn using telecom data. Performed EDA, preprocessing, and feature engineering, and handled class imbalance using sampling techniques.

🔍 Problem Statement
Customer churn is a major challenge for telecom companies, as losing existing customers directly impacts revenue. The goal of this project was to predict whether a customer is likely to churn based on their demographic and service usage data.

📊 Dataset
Telco Customer Churn dataset
Includes features like:
Customer demographics
Subscription details
Payment methods
Service usage patterns

⚙️ Approach
Performed Exploratory Data Analysis (EDA) to identify patterns and key churn indicators
Applied data preprocessing:
Handling missing values
Encoding categorical variables
Feature scaling
Conducted feature engineering to improve model performance
Addressed class imbalance using:
Undersampling
Oversampling techniques

🤖 Models Used
Logistic Regression
Decision Tree
Random Forest

📈 Results
Best performance achieved with Random Forest after oversampling
Accuracy: 83%

Identified key churn factors such as:
Contract type
Monthly charges
Tenure
Internet services

🛠 Tools & Technologies
Python
Pandas, NumPy
Scikit-learn
Matplotlib, Seaborn

💡 Key Insights
Customers with short tenure and high monthly charges are more likely to churn
Contract type (month-to-month) plays a major role in churn behavior
Proper handling of imbalanced data significantly improved model performance

🚀 Outcome
This project demonstrates how machine learning can help telecom companies identify at-risk customers and take proactive retention measures, ultimately improving customer satisfaction and reducing revenue loss.
