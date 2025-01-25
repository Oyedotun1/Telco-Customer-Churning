# Telco-Customer-Churning
This repository contains a machine learning project that predicts customer churn for a telecommunications company using supervised learning techniques. The project includes data preprocessing, model training, and evaluation using algorithms such as Support Vector Machine (SVM) and Decision Tree.




Business Need and Prediction
The model addresses a business need in the telecommunications industry, where reducing customer churn is critical for profitability. Customer churn leads to revenue loss, as it is more expensive to acquire new customers than to keep existing ones. This model predicts whether a customer is going to churn based on their past interactions, demographic data and service usage. By accurately predicting churn, the company can implement strategies to keep their customers and to improve customer loyalty and reduce churn rates.

Features and Label
The Telco Customer Churn dataset includes several features that influence whether a customer will churn. These features include:
•	Tenure (Regression): The number of months the customer has been with the company.
•	Contract Type (Categorical): The type of contract (e.g., month-to-month or yearly contract)
•	Monthly Charges (Regression): The customer’s subscription bill.
•	Payment Method (Categorical): Method of payment whether credit card or debit card
•	CustomerID (String): Unique Identifier of customer
•	Gender (Categorical)
•	Senior Citizen (Binary): Yes or No
•	Partner (Binary): Whether the customer has a partner
•	Dependents (Binary): Whether the customer has dependents
•	Internet Service (Categorical): Type of internet Services 
•	Phone Service (Binary): Whether the customer has phone service.
•	Multiple lines (Categorical): Whether the customer has multiple lines or not

Data source
The data is sourced from Kaggle
Citation: Kaggle – Telco Customer Churn Dataset https://www.kaggle.com/datasets/blastchar/telco-customer-churn

Model Implementation
This model will be used to market and used by customer service teams of the telecommunication company. The model would predict customers at high risk of churning, allowing these teams to take prevention actions, such as offering discounts or improving service quality. The model could be integrated into the company’s CRM system to automatically flag customers, helping agents prioritize outreach.


## How to Use:
1. Clone or download the repository to your local machine.
2. Ensure you have Python and the required libraries installed.
3. Run the `Customer_Churning_Split.py` script to preprocess the data and split it into training, testing, and validation sets.
4. Run `SVM_Model.py` to train and evaluate the Support Vector Machine model.
5. Run `Decision_Tree_Model.py` to train and evaluate the Decision Tree model.
6. Use `Fine_Tuning.py` to fine-tune the models and improve their performance.
