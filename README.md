# P2P_Lending_Club
This project was to build a robotic algorithm for P2P lending platform to predict the default rate and fully-paid probability of a loan to maximize user’s ROI
1. The training data can be downloaded from here: https://www.lendingclub.com/info/download-data.action
2. The training data contains various issued loan features, such as grade, subgrade, total amount. We only select 36 month loan to begin with. the target variable is loan_status. It's a binary classification machine learning problem. Charged off + Default: 1, Fully paid: 0.
3. I requested current loan listings by using Lending Club API. Current loan listings will be used as data input to predict loan default probability.
4. Performed data cleaning and feature engineering.
5. Built classification models, performed modele tuning.
