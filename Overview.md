# Flight-Price
## Hello people! Do you mind if I tell you the prices of your next flight post covid-19? 
### This tool helps you predict the prices of flights pan India for a number of Airlines. -- Special thanks to krish naik for guiding through this project and Nikhil Mittal for providing the dataset. 
#### Step 1: Importing data. 
You can download the dataset from here: https://www.kaggle.com/nikhilmittal/flight-fare-prediction-mh/
#### Step 2: Exploratory Data Analysis. 
There are 11 features present in the dataset. 
[![f1.png](https://i.postimg.cc/MGkPPXp8/f1.png)](https://postimg.cc/ts5N7q6r)
#### 2.1 Feature Engineering. 
Converted Categorical data into numerical data using OnehotEncoding and LabelEncoding depending on type of feature. 
[![f2.png](https://i.postimg.cc/mr5QX5w1/f2.png)](https://postimg.cc/4Kp7nwjX)
#### Feature Selection. 
For feature selection, we used the following techniques. 
1. heatmap
2. feature_importance_
3. SelectKBest
[![f3.png](https://i.postimg.cc/kXsRYHMM/f3.png)](https://postimg.cc/svB2vwZb)
#### Model Selection. 
For Model selection, we used RandomForest Regressor to predict flight prices. 
[![random.png](https://i.postimg.cc/JnSBq8NB/random.png)](https://postimg.cc/bDHJyKFz)
[![f4.png](https://i.postimg.cc/wT1Ynygt/f4.png)](https://postimg.cc/8jgY6CFD)
#### Hyperparamter Tuning
Choose following method for hyperparameter tuning to select best parameters for RandomForestRegressor. 
1. RandomizedSearchCV --> Fast
2. GridSearchCV
#### R2 Score: 
Obtained an R2  score of 0.794.
#### Final Accuracy = 79.4%
