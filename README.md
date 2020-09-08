## Student Income Prediction

Predicting income of a student based on data related to his major and university attended. 

### Data Source

College Scorecard Data: https://collegescorecard.ed.gov/data/documentation/ <br/>
College Scorecard API: https://collegescorecard.ed.gov/data/

### Classification Models 

#### Logistic Regression

Classified a student's income based on the median income from the data.

Class 0: Student income < Median income <br/>
Class 1: Student income > Median income


#### Multinomial Logistic Regression

Classified a student's income in 3 classes.

Class 0: Student income < 25th percentile of income <br/>
Class 1: 25th percentile of income < Student income < 75th percentile of income <br/>
Class 2: Student income > 75th percentile of income


### Regression Models

#### Linear Regression

Predicted a student's income using simple linear regression.


#### Sparse Regression (LASSO)

Predicted a student's income using linear regression with L1 penalty.
RMSE = ~12000


#### Decision Tree and Random Forest 

Predicted a student's income using using a decision tree and then a random forest regressor.
RMSE = ~15000


### Reference Paper

http://cs229.stanford.edu/proj2015/209_report.pdf
