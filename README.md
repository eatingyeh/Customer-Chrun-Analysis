# Customer-Chrun-Analysis
## 1. Goal
To do credit card customers analysis and find out possible reasons to customers churning. At the last section, I'll also build a clustering model to further perform customers observation.

## 2. Dataset
Download from: https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers

Number of Instances: 10127 with 23 variables (the last 2 naive bayes variables will be dropped)

Definition: 
- CLIENTNUM: Client number. Unique identifier for the customer holding the account
- Attrition_Flag: Internal event (customer activity) variable - if the account is closed then 1 else 0
- Customer_Age: Customer's Age in Years
- Gender: Customer Gender - M=Male, F=Female
- Dependant_count: Number of dependents
- Education_Level: Educational Qualification of the account holder (example: high school, college graduate, etc.)
- Marital_Status: Married, Single, Divorced, Unknown
- Income_Category: Annual Income Category of the account holder (< 40K, 40K - 60K, 60K - 80K, 80K-120K, >
- Card_Category: Type of Card (Blue, Silver, Gold, Platinum)
- Months_on_book: Period of relationship with bank
- Total_Relationship_Count: Total no. of products held by the customer
- Months_Inactive_12_mon: No. of months inactive in the last 12 months
- Contacts_Count_12_mon: No. of Contacts in the last 12 months
- Credit_Limit: Credit Limit on the Credit Card
- Total_Revolving_Bal: Total Revolving Balance on the Credit Card
- Avg_Open_To_Buy: Open to Buy Credit Line (Average of last 12 months)
- Total_Amt_Chng_Q4_Q1: Change in Transaction Amount (Q4 over Q1)
- Total_Trans_Amt: Total Transaction Amount (Last 12 months)
- Total_Trans_Ct: Total Transaction Count (Last 12 months)
- Total_Ct_Chng_Q4_Q1: Change in Transaction Count (Q4 over Q1)
- Avg_Utilization_Ratio: Average Card Utilization Ratio

## 3. Tools and Algorithms
Algorithms
- Kmeans Clustering

## 4. Procedure
- Files and libraries loading
- Data Preprocessing
- Exploratory Data Analysis
- Data Training
- Kmeans modeling
- Cluster Analysis

## 5. Results
Please view the code here [https://github.com/eatingyeh/Customer-Chrun-Analysis/blob/main/Customer%20Churn%20Analysis.ipynb].
