# Customer_Retention_Predictor
Evaluate which customers should be contacted to retain using an ANN


## Problem Statement

`Customer churn`` occurs when customers stop doing business with a company, also known as customer attrition. It is also referred to as loss of clients or customers.

Imagine the following data set contains sensitive information of 9,000 of a European Bank, EBQ. Using an Artificial Neural Network (ANN) based on the dataset we will attempt to correctly predict who is going to leave next. Here is a breakdown of the features in the dataset

    CustomerId: a unique identifier for each customer within the dataset. These values are not ordered sequentially within the dataset, and are only used to identify a specific customer. It typically does not have any influence to whether a customer leaves the business.
    Surname: A string used to identify the customer in the dataset. Surname may be distinct amidst all or most customers. Because of this, it most likely won't affect the target variable.
    CreditScore: a numeric representation of the customer's individual fiscal credit score. Typically used to indicate eligibility for loans. Current credit scores use a range from 300 to 850, but the FICO auto score range uses 250-900. This feature likely determines retention rate of customers.
    Geography: this feature contains a categorical string representing the name of a country the customer is from originally.
    Gender: this feature contains a categorical string representing the gender of the customer ("Male"/"Female").
    Age: a numerical integer representation of a customer's age. Intuition suggests that older customers are likely to have higher retention than younger customers.
    Tenure: a numerical integer representation. It is assumed that this feature represents the number of total years the customer has been retained. It is likely that customers which have been retained longer will continue to be retained.
    Balance: a numerical floating point number (to two decimal places of precision) indicating the customer's current bank balance (assumed total across all accounts). Customers with a greater balance may be less likely to exit the account due to difficulty of transfer.
    NumOfProducts: numeric integer value. It is assumed that this value represents the number of accounts (products) that this customer has open. Further evaluation of this feature would be needed to determine the usefulness of this feature, but at face-value, intuition dictates that a customer with more products is less likely to exit.
    HasCrCard: boolean flag (0 or 1) representing whether the customer has a credit card or not.
    IsActiveMember: boolean flag (0 or 1) representing whether the customer is an active member of the bank. It is assumed this indicates whether the customer has transactions on the regular banking statement. Intuition dictates that inactive members are more likely to exit.
    EstimatedSalary: numerical floating point representation of the customer's predicted salary (to two decomal places) intuition dictates that customers with different incomes may behave differently with respect to retention rate.
    Exited: boolean flag (0 or 1) representing whether the customer has exited their account. This is the target variable for the dataset.

