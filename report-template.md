# Report: Predict Bike Sharing Demand with AutoGluon Solution
#### RUTH NDUTA

## Initial Training
### What did you realize when you tried to submit your predictions? What changes were needed to the output of the predictor to submit your results?
- Initially, the submission failed giving an error for the date time data type to be converted to string from datetime.
- Having negative values in the predictions may have also prohibited the submission from getting through since after replacing the negatives with zero it was successful.

### What was the top ranked model that performed?
- The WeightedEnsemble_L3 performed best with a score value of 7.214185.

## Exploratory data analysis and feature creation
### What did the exploratory analysis find and how did you add additional features?
- Data imbalance in the columns e.g the weather column where category 4 had only one entry.

| Weather | Count |
|---------|-------|
| 1       | 7192  |
| 2       | 2834  |
| 3       | 859   |
| 4       | 1     |

- Holiday column also had uneven data distribution which is understandable since we have fewer holidays compared to working days

| Holiday | Count |
|---------|-------|
| 0       | 10575 |
| 1       | 311   |

### How much better did your model preform after adding additional features and why do you think that is?
TODO: Add your explanation

## Hyper parameter tuning
### How much better did your model preform after trying different hyper parameters?
TODO: Add your explanation

### If you were given more time with this dataset, where do you think you would spend more time?
TODO: Add your explanation

### Create a table with the models you ran, the hyperparameters modified, and the kaggle score.
|model|hpo1|hpo2|hpo3|score|
|--|--|--|--|--|
|initial|?|?|?|?|
|add_features|?|?|?|?|
|hpo|?|?|?|?|

### Create a line plot showing the top model score for the three (or more) training runs during the project.

TODO: Replace the image below with your own.

![model_train_score.png](img/model_train_score.png)

### Create a line plot showing the top kaggle score for the three (or more) prediction submissions during the project.

TODO: Replace the image below with your own.

![model_test_score.png](img/model_test_score.png)

## Summary
TODO: Add your explanation
