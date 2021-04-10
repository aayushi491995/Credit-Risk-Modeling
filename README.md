# Credit-Risk-Modeling
Implement a model that predicts loan or default based on the data provided.

### Objective
When a customer applies for a loan, banks and other credit providers use statistical models to determine whether or not to grant the loan based on the likelihood of
the loan being repaid. The factors involved in determining this ikelihood are complex, and extensive statistical analysis and modeling are required to predict the outcome for each individual case. Implement a model that predicts loan repayment or default based on the data provided.


### The dataset consists of the following fields:
    • Loan ID: A unique Identifier for the loan information.
    • Customer ID: A unique identifier for the customer. Customers may have more than one loan.
    • Loan Status: A categorical variable indicating if the loan was paid back or defaulted.  - Target Variable
    • Current Loan Amount: This is the loan amount that was either completely paid off, or the amount that was defaulted.
    • Term: A categorical variable indicating if it is a short term or long term loan.
    • Credit Score: A value between 0 and 800 indicating the riskiness of the borrower’s credit history.
    • Years in current job: A categorical variable indicating how many years the customer has been in their current job.
    • Home Ownership: Categorical variable indicating home ownership. Values are "Rent", "Home Mortgage", and "Own". If the value is OWN,then the customer is a home owner with no     mortgage
    • Annual Income: The customer's annual income
    • Purpose: A description of the purpose of the loan.
    • Monthly Debt: The customer's monthly payment for their existing loans
    • Years of Credit History: The years since the first entry in the customer’s credit history 
    • Months since last delinquent: Months since the last loan delinquent payment
    • Number of Open Accounts: The total number of open credit cards
    • Number of Credit Problems: The number of credit problems in the customer records.
    • Current Credit Balance: The current total debt for the customer
    • Maximum Open Credit: The maximum credit limit for all credit sources.
    • Bankruptcies: The number of bankruptcies
    • Tax Liens: The number of tax liens.
    
#### Machine Learning Steps followed to predictthe Loan status:
    1. Load the Dataset 
    2. Data Cleaning to fill missing values and remove unwanted values.
    3. Preprocesing the data of Categorical variables.
    4. Apply Different models in order to get the best models:
        i.  Applying Logistic Regression 
            - accuracy score - 0.79680
        ii. DecisionTree
            - accuracy score - 1.0
        iii. Apply DecisionTree classifier using GridSearchCV 
            - accuracy score - 0.82182
        iv. Random Forest
            - accuracy score - 0.99290
    5. Performance on Test Data
            - accuracy score - 0.65728


