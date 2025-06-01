# predicting-bankruptcy

## Project Overview
This is a SAS based machine learning project where the aim was to predict if a firm was going to declare bankruptcy or not. The data had 65 columns in total, 64 predictors and 1 target variable. More information about the columns can be found in the data dictionary. We also had access to the following files:

File descriptions
bankruptcy_Train.csv - the training set with 64 predictors and 1 target variable
bankruptcy_Test_X.csv - the test set with ID and 64 predictors
bankruptcy_sample_submission.csv - the sample submission with ID and the predicted probability of firm bankruptcy

## Data Preprocessing and Model Building

We went with a 80-20 train-test split while evaluating models so as to give the model enough data points to train on. We also handled outliers by checking the Median Absoulte Deviation and replaced outlier values with the median values of the columns, as opposed to removing it. With variable transformations, we tried binning and log transformation, but the results were not encouraging and hence, we chose to go ahead without doing any variable transformations.

As for the models itself, we found most success with an ensemble model of gradient boosted trees and neural networks. The model details and our learnings can be found in the Final Presentation powerpoint presentation.

## SAS Files

Unfortunately the SAS files were too large to upload on to Git. If you want to learn more about how I created the models on SAS Enterprise Miner, you can reach out to me on baskar2@purdue.edu or abhishekbaskar13@gmail.com and I'd be happy to share a Google Drive link of the files with you.
