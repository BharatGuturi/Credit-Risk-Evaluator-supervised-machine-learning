# supervised-machine-learning-challenge

Lending services companies allow individual investors to partially fund personal loans as well as buy and sell notes backing the loans on a secondary market.
This project creates machine learning models to classify the risk level of given loans. 
This project compares two models on this data: a Logistic Regression, and a Random Forests Classifier. 

# Data Processing

1) Load data
2) Scale data
3) Split data
4) Train models(Logistic Regression & RandomForestClassifier)
5) Output classification_report(check accuracy rate)

# Instructions:

To run this repo, execute the following commands:

  1) Git clone https:https://github.com/BharatGuturi/supervised-machine-learning-challenge.git
  2) Execute the jupyter notebook "Credit Risk Evaluator" to run the models.
  
 # Summary
 
This process will run two models on this data: a Logistic Regression, and a Random Forests Classifier.

At first glance, the data has 6 features, all data types are numeric. However some columns have a linear relationship between them(['debt_to_income']=['total_debt']/['borrower_income']) and also ['number_of_accounts'] seems not a factor to verify a person's payback ability. Therefore, the number of explanatory variables is 4 ,and the number of noise variables is 2.

Based on the analysis, the linear regression model and random forest classifer model scores were very close to each other. The predicting and training scores for both models was more than 0.99. However, the accuracy of the random forest classifier model was better than the accuracy from logistic regression.
