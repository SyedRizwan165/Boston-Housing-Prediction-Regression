# Boston Housing Prediction Analysis

# Dataset Information

The Boston House Prices Dataset, compiled in 1978, comprises 506 entries detailing properties across multiple suburban areas in Boston. Each entry includes 14 attributes or features describing the homes.

# Attributes
```
Boston Housing Dataset Attribute Information (in order):
        - CRIM     per capita crime rate by town
        - ZN       proportion of residential land zoned for lots over 25,000 sq.ft.
        - INDUS    proportion of non-retail business acres per town
        - CHAS     Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
        - NOX      nitric oxides concentration (parts per 10 million)
        - RM       average number of rooms per dwelling
        - AGE      proportion of owner-occupied units built prior to 1940
        - DIS      weighted distances to five Boston employment centres
        - RAD      index of accessibility to radial highways
        - TAX      full-value property-tax rate per $10,000
        - PTRATIO  pupil-teacher ratio by town
        - B        1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
        - LSTAT    % lower status of the population
        - MEDV     Median value of owner-occupied homes in $1000's
```
# Dataset
The dataset is taken from https://www.kaggle.com/puxama/bostoncsv

# Models Used
The models used in the report are :
    Linear Regression
    Decision Tree
    Random Forest
    Extra Tress
    XGBoost

- Further, hyper parameter tuning has been done for Random forest and XGBoost. 
- XGBoost performs relatively well than the other models with the Mean Squared Error of 6.1 and the Cross Validation Score of 20 approximately. 
# Boston-Housing-Prediction-Regression
