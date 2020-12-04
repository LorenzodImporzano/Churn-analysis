# Churn-analysis
This is the code I wrote, alongside with Mattia Ravasio and Pietro Marini, for the November hackathon organised by Bocconi Students for Data Science. 
The aim of this competition was to create a machine learning algorithm that predicts the churn rate of a telecommunication company (where the churn is whether a customer will leave or not the company).

After some model evaluations we have decided to combine three models: XGBoost, RandomForest and LogisticRegression.
In the jupyter notebook atached you can find at the beginning the training part of the algorithm (with ditailed explanaitions of the procedure) and at the end the final code that can be used directly for the churn analysis.

Our data set had the following variables:
1) “gender”, Whether the customer is a male or a female
2) “Partner”, Whether the customer has a partner or not (Yes, No)
3) “PhoneService”, Whether the customer has a phone service or not (Yes, No)
4) “InternetService”, Customer’s internet service provider (DSL, Fiber optic, No)
5) “OnlineSecurity”, Whether the customer has online security or not (Yes, No, No
internet service)
6) “Contract”, The contract term of the customer (Month-to-month, One year, Two year)
7) “PaymentMethod”, The customer’s payment method (Electronic check, Mailed check,
Bank transfer (automatic), Credit card (automatic)
8) “MonthlyCharges”, The amount charged to the customer monthly
9) “TotalCharges”, The total amount charged to the customer
10) “Churn”,Whether the customer churned or not (Yes or No)

For this algorithm, which reached a 80.04% accuracy of the prediction when tested by the judges of the competition, we were enlisted among the three winning groups.
