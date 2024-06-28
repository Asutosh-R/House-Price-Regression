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

Missing Value in Data:

![download](https://github.com/Asutosh-R/House-Price-Regression/assets/85886921/6f47f6f0-a9c3-4ee7-934a-4cb0fca552c4)

Saleprice Distribution:

![download](https://github.com/Asutosh-R/House-Price-Regression/assets/85886921/2c639224-7b53-45c7-8bbf-f5fb4339eedd)

Overall Heatmap of all Features:

![download](https://github.com/Asutosh-R/House-Price-Regression/assets/85886921/434efeaa-d42f-4e41-a337-9813f5341850)


Top Correlation:

![download](https://github.com/Asutosh-R/House-Price-Regression/assets/85886921/8a6555a1-3c71-4770-ac06-d12ad23b53a5)


OverallQual and GrLivArea seem to be the most correlated to SalePrice. 
Some of the features have multi colineariy with each other so after checking all the values the best 7 features for the data are OverallQual, GrLivArea, GarageArea, TotalBsmtSF, FullBath, YearBuilt, and YearRemodAdd.

![download](https://github.com/Asutosh-R/House-Price-Regression/assets/85886921/a6376a88-fb8e-470e-8d5b-8542cd00beb9)

![download](https://github.com/Asutosh-R/House-Price-Regression/assets/85886921/78294bfd-bee4-4670-bffa-c32d06a8c68d)

![download](https://github.com/Asutosh-R/House-Price-Regression/assets/85886921/e29f4e1e-f995-4054-a6bf-84e91c2f9370)

![download](https://github.com/Asutosh-R/House-Price-Regression/assets/85886921/b117b2ce-382e-44c1-9644-504a6e7a8e5e)

![download](https://github.com/Asutosh-R/House-Price-Regression/assets/85886921/7b513cf3-4b57-4717-9e20-d85c3e381863)

![download](https://github.com/Asutosh-R/House-Price-Regression/assets/85886921/e6283a18-a208-4299-8452-180de3ce3232)


![download](https://github.com/Asutosh-R/House-Price-Regression/assets/85886921/64e4009b-6b21-43e9-9507-0c6cc6e2c7a2)

Removing outlier from the Targeted Feature of train data

![download](https://github.com/Asutosh-R/House-Price-Regression/assets/85886921/bc223436-b745-459c-bcf1-ae28078f67a8) 

After performing cross-validation using five different models—Linear Regression, Ridge Regression, Lasso Regression, RandomForest Regression, and Gradient Boosting Regression—I determined that the Gradient Boosting algorithm achieved the highest accuracy. Subsequently, I trained the model using x_train and y_train, and proceeded to predict the target values for the test dataset.
