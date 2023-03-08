# Random_Forests
Random Forest is a type of ensemble machine learning algorithm that combines the predictions of multiple decision trees to improve the accuracy and robustness of the model. 
When making a prediction, the Random Forest algorithm aggregates the predictions of all the individual trees in the forest and returns the most common prediction. This approach helps to reduce overfitting and improves the accuracy of the model.
# CHURN_MODELLING DATASET
In this data set the Random Forest Mean Squared Error(RFMSE) was 0.02 in training the models. This means that the predicted values from the random forest model have a low average squared difference from the actual values in the training dataset After combining models, the output of Random Forest Mean Squared Error: 0.1143. This value indicates how well the combined model is performing in predicting the target variable.

After evaluating the ensemble the output is Random Forest 1 Mean Squared Error: 0.11, Random Forest 2 Mean Squared Error: 0.11, Linear Regression Mean Squared Error: 0.14, Voting Regressor Mean Squared Error: 0.11 and Stacking Regressor Mean Squared Error: 0.11. This concludes that the results indicate that the ensemble method of combining different models produced a lower mean squared error than using any individual model alone.All of the random forest models and the voting regressor have roughly the same mean squared error, indicating that they perform similarly well.However, the linear regression model has a higher mean squared error, indicating that it does not predict the target variable as well as the other models. With the lowest mean squared error, the stacking regressor may be the best model for making predictions on this dataset.

In tuning the ensemble the output is Random Forest Mean Squared Error: 0.1143 and Random Forest R-squared Score: 0.2759. This means the Random Forest model's mean squared error has decreased to 0.114, indicating that the model's performance has improved. The Random Forest model's R-squared score has also increased to 0.276, indicating that the model can explain 27.6% of the variance in the target variable. This indicates that tuning the ensemble has improved the Random Forest model's performance, making it a better predictor of the target variable.

# INSUARANCE DATASET
Using the insuance csv , i performed a predictive analysis folllowing these steps:
step 1: Importing necessary libraries and loading the dataset to begin the EDA.
Step 2: perform Exploratory Data Analysis (EDA)
step 3: Training the Models
step 4: Combining the Models
step 5:Evaluating the Ensemble
step 6: Tuning the Ensemble
