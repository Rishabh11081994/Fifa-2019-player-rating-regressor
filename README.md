# Fifa-2019-player-rating-regressor
Estimating overall rating of player


Here in the jupyter notebook efforts were taken to estimate the rating of player usinf fifa dataset taken from kaggle. The whole purpose is to predict the rating bases on 85 features which includes skills, value, wages, fiedl positioning, nationality clubs etc. 

The approach is mentioned below:

1. Prepprocesing is done which includes cleaning of fields, treating null and duplicated values
2. Data exploration was done after that
3. Linear regression model was built as model and insignificant variables were removed suing backward selection method
4. Other models were build , analyzed and compared . Some models name are support vector regressor, decision tree regressor, gradient boosting, xgboost, random forest etc.
5. Overfitting and underfitting problems were checked
6. Assumption of linear regression is checked to make sure the model is alright
7. Conclusion are drawn and model is selected for deployment. 
