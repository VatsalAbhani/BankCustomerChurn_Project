**Customer Churn Prediction and A/B Testing**

This project involves building a machine learning model to predict customer churn using a Random Forest classifier. 
It also includes an A/B testing framework to evaluate the effectiveness of a personalized retention strategy. 
Additionally, key insights from the data and model performance were visualized using Tableau dashboards.

The dataset used is 'Bank Customer Churn Prediction' from Kaggle. The dataset includes the following attributes:

- Customer ID: A unique identifier for each customer
- Surname: The customer's surname or last name
- Credit Score: A numerical value representing the customer's credit score
- Geography: The country where the customer resides (France, Spain or Germany)
- Gender: The customer's gender (Male or Female)
- Age: The customer's age.
- Tenure: The number of years the customer has been with the bank
- Balance: The customer's account balance
- NumOfProducts: The number of bank products the customer uses (e.g., savings account, credit card)
- HasCrCard: Whether the customer has a credit card (1 = yes, 0 = no)
- IsActiveMember: Whether the customer is an active member (1 = yes, 0 = no)
- EstimatedSalary: The estimated salary of the customer
- Exited: Whether the customer has churned (1 = yes, 0 = no)

Results

- Churn Prediction Model: Achieved 86% accuracy using a Random Forest classifier.
- A/B Testing Results: The treatment group showed an 18% reduction in churn compared to the control group, validated through statistical significance testing.
- Business Impact: Provided actionable insights into customer behavior, allowing for targeted interventions to reduce churn.

Technologies Used
Languages: Python (pandas, scikit-learn)
Visualization: Tableau
Libraries: scikit-learn, matplotlib, seaborn, Jupyter Notebook
