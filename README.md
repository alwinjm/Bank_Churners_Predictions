# Bank Churners Prediction Project
The data for this project was provided through 'BankChurners.csv' found on kaggle under this url: https://www.kaggle.com/sakshigoyal7/credit-card-customers.

## Objective
The problem at hand is that of a bank manager who is faced with an increasing number of customers cancelling their credit card accounts. In order to prevent further loss of customers, the bank manager requires a model that is able to predict the customers that are going to cancel their credit cards so that they can be encouraged to retain instead of cancelling. 

## Set-Up
It has been assumed that the user has python installed on their machine with all basic libraries such as Pandas, Numpy, scikit-learn, matplotlib, and seaborn. If yes, then proceed to:

- Download `BankChurners.csv` from the aforementioned URL.
- Read the csv file into a new python file.
- Install imblearn using the command ```pip install imblearn```
- Install xgboost using the command ```pip install xgboost```

## Exploratory Data Analysis
`BankChurners.csv` should contain the following columns/features:

- **Attrition_Flag:** Existing Customer, Attrited Customer
- **Gender:** M, F
- **Education_Level:** Unknown, Uneducated, High School, College, Graduate, Post-Graduate, Doctorate
- **Marital_Status:** Unknown, Single, Married, Divorced
- **Income_Category:** Less than $40K, $40K - $60K, $60K - $80K, $80K - $120K, $120K +, Unknown
- **Card_Category:** Blue, Silver, Gold, Platinum
- **Customer_Age:** Customer's age in years
- **Dependent_count:** Customer's number of dependents
- **Months_on_book:** Number of months the credit card holder has been a customer of the bank
- **Total_Relationship_Count:** Total number of products possessed by the customer
- **Months_Inactive_12_mon:** Number of months the customer has been inactive in the last 12 months
- **Contacts_Count_12_mon:** Numer of contacts with the customer in the last 12 months
- **Credit_Limit:** Customer's maximum credit allowance
- **Total_Revolving_Bal:** Total revolving balance on the customer's credit card
- **Avg_Open_To_Buy:** Average open to buy credit line in the last 12 months
- **Total_Amt_Chng_Q4_Q1:** Difference in transaction amount from Q4 to Q1 
- **Total_Trans_Amt:** Total amount transferred in the last 12 months
- **Total_Trans_Ct:** Total number of transactions in the last 12 months
- **Total_Ct_Chng_Q4_Q1:** Change in transaction count from Q4 to Q1 
- **Avg_Utilization_Ratio:** Average card utilization ratio 
  

