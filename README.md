This flood prediction model uses LGBM Regression model with hyperparameter tuning after careful consideration of the results. The parameters were selected by experimentation.

My personal approach was:



1. study the data and find out the insights: all the columns were numerical and null values weren't present.



2. EDA: Exploratory Data Analysis using heatmap and histograms.



3. Feature Engineering: Use of various factors like mean, median, sum, etc for adding more features to the base features.



4. Model Hit-and-trial: There was no way to know which model would work better. Hence, I tried linear regression which was obviously a bad choice. Random Forest regression was fine but wasn't enough. Ensemble learning sort of ruined the R2-score. In the end, LGBM regressor made it through.

The original notebook:
https://www.kaggle.com/code/themajormask/flood-prediction/notebook
