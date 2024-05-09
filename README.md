Module 20 Challenge - Credit risk classification

OVERVIEW
The analysis was completed using a logistic regression model to determine credit risk in making loans. The data included the size and interest rate of the loan, borrower income, the borrower's debt to income ration, the number of accounts they hold, derogatory marks on their credit report, the total amount of their debt, and loan status. Loan status is the dependent variable - the other variables are used to predict a healthy loan or a high risk loan. The dependent variable is binary, with a value of 0 for healthy or 1 for high risk. After loading the data, the data was split into training and testing sets. From there, using LogisticRegression from the sklearn package, a logistic regression model was created and fitted using the original training data created in the previous step. The dependent variable was predicted using the model and compared to actual results, and the model's performance was evaluated with a confusion matrix - which gives a rundown of how predicted values performed against actuals, and a classification report showing precision, recall, and f1 scores. 

RESULTS
•The accuracy of the model is high - at 0.94 it is accurately predicting the dependent variable 94% of the time. 
•The model predicts healthy loans with perfect accuracy, recall, ad f1 scores of 100%. 
•The model is less accurate, but still overally very effective, at predicting high risk loans, with a precision score of 87%, recall of 89%, and an f1 score of 88%. 

SUMMARY
The model is very accurate at predicting both healthy loans and high risk loans - more so with healthy loans than high risk loans but predicts both very well. This also suggests that the independent variables are all very useful in predicting the dependent variable. It is a very strong model and could be used as an accurate tool to predict a high risk loan and I could recomment it for use by the company.
