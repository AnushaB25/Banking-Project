# Banking-Project
This is a classification dataset where we have to predict weather the networth of the company will increase or decrease next year based on previous year data.
All the necessary libraries are imported; and than basic eda was performed where we can see that there are 3541 rows and 52 columns in this dataset.
Also many columns consist of null values as well.
Initially the data cleaning was done where the column names were renamed, target variable was continuous which was converted to classification data.
Then the null values were dropped for all columns where total percent of null values were greater than 30 as its difficult to treat them.
The remaining null values were treated using IQR (inter-quartile range).
Once the cleaning part was completed; data was splitted into X and y and all the necessary models were imported.
Models like : Logistic Regression, KNN, Decision Tree was build on the data and hyperparameter tuning was performed to get the best model.
The best model for this dataset is KNN from which we are getting 95.02% accuracy. Paramaters are : Kernel : Linear, Gamma : 0, C : 0.1
