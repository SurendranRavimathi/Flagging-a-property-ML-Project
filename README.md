# Real_estate_Project_Python
Formal Problem Statement 
Variable names are self explanatory and there is no formal data dictionary provided by the client . Your task here is to build a predictive model for predicting whether a property should be marked as junk on the basis of listing details and preliminary assessment details. You need to build your model on the train dataset. Test dataset does not have a response column; you need to predict those values and submit it in a csv format.

for more infomation kindly find the problem statement.pdf in the repo

Flagging a property: The real estate client wanted to predict the probabilities of property which is going to be unfit using its property history and demography details.

Solution: Used XGBoost to create a ML model to predict the probabilities of unfit properties (classification problem). The model had
a roc_auc score of 0.78 (Python).

Base line score: 0.65

