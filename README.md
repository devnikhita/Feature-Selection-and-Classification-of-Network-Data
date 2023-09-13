# GDSC
GDSC - ML Recruitment Assignment

STEP 1:  IMPORTING LIBRARIES

warnings - to ignore any warnings with the word 'deprecated'

numpy - for linear algebra

pandas - for data processing


STEP 2:  MOUNTING DRIVE

The given dataset has been uploaded to the drive so that it can be accessed by colab notebook.


STEP 3:  READING THE DATASET

The given dataset is read into a dataframe.


STEP 4:  DATA CLEANING

The dataframe is checked for null values.

Infinite values are replaced with NaN values.


STEP 5:  DATA TRANSFORMATION

Label Encoder is used to convert 'object' type into 'integer'.

Null values are dropped from the dataset.


STEP 6:  FEATURE EXTRACTION

Decision Tree Classifier is used to select top 20 features for easy analysis.


STEP 7:  ML MODEL IMPLEMENTATION

Accuracy, Precision, Recall, F1 Score, Confusion Matrix and Balanced Accuracy are calculated using the following models:

a) Logistic Regression

b) Random Forest Classifier


CONCLUSION:

Compared to Logistic Regression, Random Forest Classifier has:

a) more accuracy

b) higher precision

c) better recall

d) better f1 score

e) fewer false positives and false negatives

f) more balanced accuracy
