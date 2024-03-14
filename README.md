# Diwali sales analysis using Python
## Introduction
This repository demonstrates Exploratory Data Analysis methods and techniques using Python. The purpose of the used Diwali Sales dataset has been taken from Kaggle since it is one of the ideal dataset for performing EDA and taking a step towards the most amazing and interesting field of data science. 
## Objective
The aim of this project is to analyse Diwali sales on the basis of diffetent products, gender, state, age, occupation and zone area of the customers. Improving customer experience by analyze sales data. Increase revenue.
##
Firstly I have to import libraries such as pandas, NumPy, matplotlib and seaborn in jupyter notebook
## Data Cleaning
To check the datatype of each column we are going to use df.info() [we have load our csv file in df] df.info() show the information such as column name, datatype, non-null count of rows, etc To delete any useless columns we run command df.drop([‘C1’,’C2'], axis=1, inplace=True)……….axis=1 is used for total row and inplace=True used for saving the changes

After removal of useless columns, we have the raw data file but it is uncleaned and contains null values. To check that null values we have to run code using pandas as pd.isnull(df).sum() When any row has null values then to eliminate such null values we call command of pd.dropna(inplace=True)

If we want to find min, max, avg, total, standard deviation, 25%, 50%, 75% etc we use df.describe()

Now after cleaning data its time to analyze data So now we are going for
# Exploratory Data Analysis (EDA)
## Gender
![Screenshot 2024-03-14 102455](https://github.com/alinasoy/Diwali-sales-analysis/assets/127585848/0869d335-cff6-4a9e-be46-07b90588031c)
![Screenshot 2024-03-14 102507](https://github.com/alinasoy/Diwali-sales-analysis/assets/127585848/7aa77695-3af6-4e92-b290-8627beeda3cc)
## Age
![Screenshot 2024-03-14 102525](https://github.com/alinasoy/Diwali-sales-analysis/assets/127585848/7d18cf5d-8506-4c3a-bbe2-71930b9fa329)
![Screenshot 2024-03-14 102539](https://github.com/alinasoy/Diwali-sales-analysis/assets/127585848/8510a784-f17f-422e-a999-732ab2e9eaa0)
## State
![Screenshot 2024-03-14 102553](https://github.com/alinasoy/Diwali-sales-analysis/assets/127585848/d90a0ea3-bcd1-4a94-9d2a-786ad1297ab1)
![Screenshot 2024-03-14 102608](https://github.com/alinasoy/Diwali-sales-analysis/assets/127585848/fd3b35a5-66ec-4c1b-b92a-a6815b702ec0)
## Marital Status
![Screenshot 2024-03-14 102629](https://github.com/alinasoy/Diwali-sales-analysis/assets/127585848/e818b46a-a1d4-471f-8475-781785cf96b5)
![Screenshot 2024-03-14 102738](https://github.com/alinasoy/Diwali-sales-analysis/assets/127585848/9da966aa-ec06-4c26-8e84-e2941face6d5)
## Occupation
![Screenshot 2024-03-14 102754](https://github.com/alinasoy/Diwali-sales-analysis/assets/127585848/97218f22-20d8-4216-9e09-c0147bfdc42a)
![Screenshot 2024-03-14 102850](https://github.com/alinasoy/Diwali-sales-analysis/assets/127585848/7ff374a1-01d3-4b55-868c-144206e4aa54)
## Product Category
![Screenshot 2024-03-14 102924](https://github.com/alinasoy/Diwali-sales-analysis/assets/127585848/5747e292-2731-4d71-b73a-36595d16cfb6)
![Screenshot 2024-03-14 102938](https://github.com/alinasoy/Diwali-sales-analysis/assets/127585848/73944237-695d-4793-bd56-7869da2edd29)
![Screenshot 2024-03-14 103000](https://github.com/alinasoy/Diwali-sales-analysis/assets/127585848/fd06f6dc-35aa-4970-8887-638aa4ad0250)
![Screenshot 2024-03-14 103024](https://github.com/alinasoy/Diwali-sales-analysis/assets/127585848/82ac0be9-fcf1-4746-b6d2-f78b02fc9f14)
## Conclusion
Married women of age group 26–35 years from Uttar Pradesh, Maharastra and Karnataka working in IT, Healthcare and Aviation are more likely to buy products from Food, Clothing and Electronics category.
