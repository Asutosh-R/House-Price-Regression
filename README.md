# House Price Regression 

Created House Price Prediction Model with 85.3% accuracy with gradient boosting model.


#### Data Set
* Kaggle data_set link: "https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data"

#### Steps Performed with dataset
* Installing Module
* Loading Data set
* Understanding Data
* Missing Value and Outliers Detection
* Removing Missing Value and Outliers
* Feature Engineering
* Cross Validation
* Model Predicting With Random Forest
* Creating Submission file

##### Train Data set info:
* There are 1460 rows and 81 columns.
* There are columns with large number of null entries like PoolQC, MiscFeature.
* The columns have Three types of datatypes: float64(3), int64(35), object(43).

##### Test Data set info:
* There are 1459 rows and 80 columns.
* There are columns with large number of null entries like PoolQC, MiscFeature etc.
* The columns have Three types of datatypes: float64(11), int64(26), object(43).

Top Correlation:

![image](https://user-images.githubusercontent.com/85886921/189496136-4212405a-cf38-4638-82ff-61257c09ecec.png)

OverallQual and GrLivArea seem to be the most correlated to SalePrice

