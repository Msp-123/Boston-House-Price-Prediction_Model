# Boston-House-Price-Prediction_Model
### Cross_val_score and GridSearchCV was used. R2 score is 0.93.

We are going to set a machine learning model to predict price of houses in Boston. To train our model with the boston housing price data, scikit-learn's boston dataset will be used. 

Definitons of the columns are 
"  
CRIM per capita crime rate by town
ZN proportion of residential land zoned for lots over 25,000 sq.ft.
INDUS proportion of non-retail business acres per town
CHAS Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
NOX nitric oxides concentration (parts per 10 million)
RM average number of rooms per dwelling
AGE proportion of owner-occupied units built prior to 1940
DIS weighted distances to five Boston employment centres
RAD index of accessibility to radial highways
TAX full-value property-tax rate per 10,000usd
PTRATIO pupil-teacher ratio by town
B 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
LSTAT % lower status of the population. "

After drawing histogram graphs of all variables, we can see that distribution of the most of variable are not similar to the Gauss Distribution. Consequently, using Min Max Scaling was decided.

Being able to predict prices in the most accurate way, 4 different regression methods will be used. These are;

  ####Linear Regression : A linear regression model describes the relationship between a dependent variable, y, and one or more independent variables, X. 
  [image](https://user-images.githubusercontent.com/83719212/208004942-55ef77a7-0f3a-43be-afa5-e40a3f9c1178.png)
  
  ####Random Forest Regressor : The basic idea behind this is to combine multiple decision trees in determining the final output rather than relying on individual decision trees. 
  [image](https://user-images.githubusercontent.com/83719212/208005056-b29911d1-8b8b-4f4c-aaa5-3b0ab9fa25eb.png)

  

