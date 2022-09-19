# Gold Mining Prediction
Prepare a prototype of a machine learning model for Zyfra. The model should predict the amount of gold recovered from gold ore.

The model should predict the amount of gold recovered from gold ore. You have the data on
extraction and purification

The model will help to optimize the production and eliminate unprofitable parameters.
You need to:
1. Prepare the data;
2. Perform data analysis;
3. Develop and train a model.

## Project description
The data is stored in three files:
- gold_recovery_train.csv — training dataset 
- gold_recovery_test.csv — test dataset 
- gold_recovery_full.csv — source dataset 

Data is indexed with the date and time of acquisition (date feature). Parameters that are next to
each other in terms of time are often similar.
Some parameters are not available because they were measured and/or calculated much later.
That's why, some of the features that are present in the training set may be absent from the test set.
The test set also doesn't contain targets.

The source dataset contains the training and test sets with all the features.


