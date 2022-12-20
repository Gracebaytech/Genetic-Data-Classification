# Genetic-Data-Classification
**Problem Domain:** The dataset is related to genomics, and that is reason why this data has a lot more columns, compared to rows, which is common in genetic/genomic dataset.
There might be similar genomic/genetic dataset related challenges in the near future and this project should help you to get familiar with datasets like these.
## CHALLENGE REQUIREMENTS
Within this goal the following are the targets:

Train a model, using the file train.csv - The train.csv file can be found in the challenge dataset folder in the forum. That file should be used to train a machine learning model. Here the last (right-most) column in the file is the label, and all other columns are features

Using the trained model, take test_x.csv as feature input and predict the probabilities of each of the 5 classes - The test_x.csv file contains the test dataset. It does NOT contain the labels. Pass these features to your 
model, and generate a prediction with 241 rows (same as test_x.csv) and 5 columns (corresponding to 5 classes), with each column containing a decimal value between 0 to 1.

## METRIC
This is a classification problem, and we'll be using the classification metric **ROC AUC Score** as the scoring metric.
