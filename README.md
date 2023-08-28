# Customer Churn Prediction using Support Vector Machines

Welcome to the Customer Churn Prediction project! This project focuses on developing a machine learning model to predict customer churn using Support Vector Machines (SVM). Predicting customer churn is vital for businesses aiming to retain their clients and improve customer retention strategies.


## Project Overview

The goal of this project is to create a predictive model that can anticipate customer churn, enabling businesses to take proactive measures to retain their valuable clientele. Customer churn analysis can provide invaluable insights for designing targeted campaigns and strategies to mitigate customer attrition.

### Dataset Description

In this analysis, we will use data provided by a multinational bank on a Kaggle competition (Identity hidden for data privacy). The data provided has the following variables:

- **RowNumber**: Corresponds to the record (row) number and has no effect on the output.
- **CustomerId**: Contains random values and has no effect on customers leaving the bank.
- **Surname**: The surname of a customer has no impact on their decision to leave the bank.
- **CreditScore**: Can have an effect on customer churn, as a customer with a higher credit score is less likely to leave the bank.
- **Geography**: A customer’s location can affect their decision to leave the bank.
- **Gender**: It’s interesting to explore whether gender plays a role in a customer leaving the bank.
- **Age**: This is certainly relevant, as older customers are less likely to leave their bank than younger ones.
- **Tenure**: Refers to the number of years that the customer has been a client of the bank. Normally, older clients are more loyal and less likely to leave a bank.
- **Balance**: Also a very good indicator of customer churn, as people with a higher balance in their accounts are less likely to leave the bank compared to those with lower balances.
- **NumOfProducts**: Refers to the number of products that a customer has purchased through the bank.
- **HasCrCard**: Denotes whether or not a customer has a credit card. This column is also relevant, as people with a credit card are less likely to leave the bank.
- **IsActiveMember**: Active customers are less likely to leave the bank.
- **EstimatedSalary**: As with balance, people with lower salaries are more likely to leave the bank compared to those with higher salaries.
- **Exited**: Whether or not the customer left the bank.
- **Complain**: Whether the customer has a complaint or not.
- **Satisfaction Score**: Score provided by the customer for their complaint resolution.
- **Card Type**: Type of card held by the customer.
- **Points Earned**: The points earned by the customer for using the credit card.


## Usage

1. **Data Preparation:** Ensure you have the necessary dataset (provide download link if available). Clean and preprocess the data using `data_preparation.ipynb`.

2. **Model Building:** Explore different SVM configurations and build the prediction model using `customer_churn_prediction.ipynb`.

3. **Evaluation:** Evaluate the model's performance using appropriate metrics and visualize the results.


## License

This project is licensed under the [MIT License](LICENSE).


