# House_Prices_xgbregressor
 xgbregressor notebook from Kaggle House Prices competition


## Data Description
With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.

I cleared the dataset from features where 50% or more of the data was missing, as well as features with a correlation of more than 0.7 to get rid of noise
Recovered missing values with SimpleImputer

Encoded the categorical data
Normalized the data with Standart Scaler

# In this notebook I use XGBoost Regressor
 Picked up the optimal parameters using RandomizedSearchCV


 Public Score 0.13007
