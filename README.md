# Loan-defaulter-Classification

This problem is about loan defaulters classifcation. This dataset contains loan data, where 500K rows and 45 columns including loan status representing the defaulters or non-defaulters. Using necessary data, I have developed a machine learning model to predict loan defaulters.

This ML model is able to predict 61% of the defaulters. It has also improved Return on Investment (ROI) of loans.

Following process have been done:

    Data loading
    Exploratory Data Analysis and Data Cleaning
      Comprison of each feature against the loan_status
      Selecting relevant feature 
      Null Value imputation
      Creating dummy variables
      Handling outliers
    
    Training a machine learning model:
 
      Models used:
         Logistic Regression
         Random Forest
         Decision Tree 
         MLP
      Performance of the model is evaluated based on AUC-ROC score
        Decision Tree gives maximum AUC-ROC score of 0.6134
  
