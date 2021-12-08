# Consumer-Loan-Default-And-Valuation

A personal project constructing a consumer loan default classifier from historical LendingClub data(https://www.kaggle.com/wordsforthewise/lending-club). The trained model is used to make predictions in the valuation notebook resulting in bifurcated assumptions being applied.

Notebook order:
1) Exploratory Data Analysis
2) Feature Engineering
3) Random Forest
4) Valuation

Note: The default classifier is trained with an F2 score to limit type II errors that originators try to avoid. Accuracy would probably be a better measure if the valuation tool is being used by a third party to make acquisitions or perform valuations. 

Future Improvements:
1) Add Logistic Regression & XGBoost model builds
2) Use a limited number of features in model training to make the default classifiers more broadly useful 
3) Add optional recovery lags on defaulted loans in valuation notebook 
