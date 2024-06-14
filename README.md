# Classification-Credit-Card-Score-Project

PROBLEM STATEMENT- You are working as a data scientist in a global finance company. Over the years, the company has collected basic bank details and gathered a lot of
credit-related information. The management wants to build an intelligent system to segregate the people into credit score brackets to reduce the manual efforts. Given a
person’s credit-related information,build a machine learning model that can classify the credit score.

DATASET INFORMATION- Credit score dataset contains 1 lac records with 28 features.

Attributes 
1. ID---> unique identification of an entry
2. Customer_ID---> unique identification of a person
3. Month---> month of the year
4. Name---> name of a person
5. Age---> age of the person
6. SSN---> social security number of a person
7. Occupation---> occupation of the person
8. Annual_Income---> annual income of the person
9. Monthly_Inhand_Salary--->monthly base salary of a person
10. Num_Bank_Accounts---> number of bank accounts a person holds
11. Num_Credit_Card---> number of other credit cards held by a person
12. Interest_Rate---> interest rate on credit card
13. Num_of_Loan---> number of loans taken from the bank
14. Type_of_Loan---> types of loan taken by a person
15. Delay_from_due_date---> average number of days delayed from the payment date
16. Changed_Credit_Limit---> percentage change in credit card limit
17. Num_Credit_Inquiries---> number of credit card inquiries
18. Credit_Mix---> classification of the mix of credits
19. Outstanding_Debt---> remaining debt to be paid (in USD)
20. Credit_Utilization_Ratio---> utilization ratio of credit card
21. Credit_History_Age---> the age of credit history of the person
22. Payment_of_Min_Amount---> the minimum amount was paid by the person
23. Total_EMI_per_month---> monthly EMI payments (in USD)
24. Amount_Invested_monthly---> monthly amount invested by the customer (in USD)
25. Payment_Behaviour---> payment behavior of the customer (in USD)
26. Monthly_Balance---> monthly balance amount of the customer (in USD)
27. Credit_Score---> the bracket of credit score

STEPS
1. I start off this project by importing all the necessary libraries that will be required for the process.
2. Loaded the data and removed unnecessary columns from the dataframe.
3. Checked the shape of a dataframe and datatypes of all columns along with calculating the statistical data.
4. Checked the missing values in a dataframe.
5. Replaced the special characters with empty string or with null values according to the data and converted them into int or float datatype. 
6. After replacing the special characters with null value. The new missing value were detected. Applied the mean imputation technique.
7. Removed the outliers.
8. Performing Label Encoding for categorical features of a dataframe.
9. Selected the features using VIF. VIF should be less than 5.
10. Perfomed model training using Decision Tree and Random Forest Classifier.
11. Performed Hyperparameter tuning to increase the accuracy.
