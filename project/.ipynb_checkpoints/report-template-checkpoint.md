# Report: Predict Bike Sharing Demand with AutoGluon Solution
#### NAME HERE
Mohamed Boghdady 
## Initial Training 1.81080
### What did you realize when you tried to submit your predictions? What changes were needed to the output of the predictor to submit your results?
TODO: after training the model for the first time, the error was high and EDA and feature engineering eas needed to reduce the error

### What was the top ranked model that performed?
TODO: Add your explanation
WeightedEnsemble_L3

## Exploratory data analysis and feature creation
### What did the exploratory analysis find and how did you add additional features?
TODO: after creation new features, EDA (correllation matrix) showed that there is a relationship between the new featurs and the target feature

### How much better did your model preform after adding additional features and why do you think that is?
TODO: Add your explanation
the score_val improved from -50 to -32 after doing EDA and feature creation, the new faetures helped the model to learn better. 
## Hyper parameter tuning
### How much better did your model preform after trying different hyper parameters?
TODO: Add your explanation: tunning the hyper parameters increases the error, I got worse score. How ever some models improved its performance but the overall result wasn't as expected

### If you were given more time with this dataset, where do you think you would spend more time?
TODO: Add your explanation
I may spend more time on feature engineering, EDA, and parameters tuning, I belive that if more time is given for this data, the performance will improve after doing some Adjustmens.
### Create a table with the models you ran, the hyperparameters modified, and the kaggle score.
|model|hpo1|hpo2|hpo3|score|
|--|--|--|--|--|
|initial|default_values|default_values|default_values|1.81080|
|add_features|default_values|default_values|default_values|0.45484|
|hpo|{'GBM': {'num_leaves': (30, 65)}}|{'XGB': {'max_depth': 11}}{'XT': {'n_estimators': 100}}|0.46373|

### Create a line plot showing the top model score for the three (or more) training runs during the project.

TODO: Replace the image below with your own.

![model_train_score.png](project/model_train_score.png)

### Create a line plot showing the top kaggle score for the three (or more) prediction submissions during the project.

TODO: Replace the image below with your own.

![model_test_score.png](project/model_test_score.png)

## Summary
TODO: Add your explanation
I have successfully installed the required libraries and imported the data. Initially, I used the regression model and obtained an error of -50. However, after performing some exploratory data analysis (EDA) and feature engineering, the error decreased significantly. Later, I attempted to tune some of the model's hyperparameters to improve its performance. However, to my surprise, the error increased again. Despite multiple attempts to tune the hyperparameters, my efforts were in vain and the error persisted. After several iterations, I was finally able to achieve the score mentioned above. Although it was a challenging process, I learned a lot about the importance of EDA, feature engineering, and hyperparameter tuning in improving the performance of machine learning models.