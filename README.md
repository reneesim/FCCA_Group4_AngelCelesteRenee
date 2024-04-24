## Background
Applying for loans is an inevitable process people would encounter at some point of their lives. The primary loan one would take up would be a housing loan, to finance ones new home. At our stage in life, applying for a Built-to-Order (BTO) flat is something many young couples are considering. However, loan application is arduous and time consuming, often ending in rejection. Unfortunately many applicants remain unaware of the specific reasons for their unsuccessful loan applications. 

## Problem Definition 
A major challenge face by loan applicants is a lack of understanding regarding the elements influence loan status. This lack of understanding means that the applicants will not be able to address the underlying issues they face, prolonging the loan application proccess. Therefore, there is a need for a solution that can assess the likelihood of loan approval and evaluate the importance of certain factors. This will provide applicants with clear and actionable steps for applicants to improve their chances of approval. 

In our dataset, we have 13 columns of data: 
   1) loan_id
   2) no_of_dependents: Number of Dependents of the Applicant
   3) education: Education of the Applicant (Graduate/Not Graduate)
   4) self_employed: Employment Status of the Applicant
   5) income_annum: Annual Income of the Applicant
   6) loan_amount: Loan Amount
   7) loan_term: Loan Term in Years
   8) cibil_score: Credit Score
   9) residential_assets_value
   10) commercial_assets_value
   11) luxury_assets_value
   12) bank_asset_value
   13) loan_status: Loan Approval Status (Approved/Rejected)
    

The standard of the credit scores is as such: 
- POOR: 300-579
- FAIR: 580-669 
- GOOD: 670-739 
- VERY GOOD: 740-799
    
## Rough Outline of our Code

*Data Preparation*: Includes cleaning of data and identifying the data types in our dataset 

*Exploratory Analysis*: Utilising a pairplot to visualise the overall relationships between variables in the dataset

*Data Visualisation*: We split this section into numerical and categorical and analysed the variables individually before removing outliers. Using Chi Square Test and ANOVA, we analysed the relationship between various variables

*Machine Learning*: Our machine learning proccess uses two models, Logistic Regression and Random Forest 

*Loan Status Prediction Program*: We came up with this program using the machine learning models we built to help users predict their loan status. If they are predicted to be rejected, we also show the factors that may contribute to the rejection.

## What we learnt from this project
- ANOVA (Analysis of Variance) to test for significant differences between group means
- Chi Square Test to exam the relationships between categorical variables 
- Logistic Regression from sklearn 
- Random Forest from sklearn 
- Concepts about Precision, Recall and F1 Score 

## Contributors
- Angel Chan Jin Xuan
- Peh Yong Qi Celeste 
- Sim Hui En Renee Nicole 

## References 
1. Koehrsen, W. (2018, January 10). Hyperparameter tuning 1the random forest in python. Medium. https://towardsdatascience.com/hyperparameter-tuning-the-random-forest-in-python-using-scikit-learn-28d2aa77dd74
2. Kai. (2023, July 16). Loan-approval-prediction-dataset. Kaggle. https://www.kaggle.com/datasets/architsharma01/loan-approval-prediction-dataset/data

