Assignment 1: Prototype

Build a prototype for email spam classification

1. in prepare.ipynb write the functions to
    - load the data from a given file path
    - preprocess the data (if needed)
    - split the data into train/validation/test
    - store the splits at train.csv/validation.csv/test.csv

2. in train.ipynb write the functions to
    - fit a model on train data
    - score a model on given data
    - evaluate the model predictions
    - validate the model
        i. fit on train
        ii. score on train and validation
        iii. evaluate on train and validation
        iv. fine-tune using train and validation (if necessary)
    - score 3 benchmark models on test data and select the best one
