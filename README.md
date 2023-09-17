# ML_Lab_1

## main steps of the function as follows

### 01 Import used libraries

### 02 Used Functions for feature engineering

  1. define the function Get data frame data removing unwanted labels and null data
  2. define the function Random Forest Classifier used to create the model
  3. define the function K-Nearest Neighbor used to create the model
  4. define the function Get the accuracy and report of the predictions
  5. define the function to select the best K number of features using sklearn SelectBest function which uses f_regression
  6. define the function Add a Principal Component Analysis(PCA) and get additional features by finding principal components

### 03 / 05 / 06 Reducing features by feature engineering of Label 01, Label 03, and Label 04

  1. Get the dataset and remove unwanted labels
  2. create a model using Random Forest before feature engineering
  3. create a model using Random KNN before feature engineering
  4. Add KNN-predicted data since it has better accuracy to CSV file
  5. Find the best k features and select
     (before selecting features check if k is enough to achieve better accuracy and finally come up with k features.)
  6. Check whether the accuracy of the selected features is enough or not using random Forester
  7. Check whether the accuracy of the selected features is enough or not using KNN
  8. Create a PCA to create new features using train data
  9. Join the newly created features with the selected features and find the status of the model using a Random forest
  10. Find the status of the model using KNN after joining PCAs
  11. Add KNN predicted data since it has better accuracy to csv file

### 04 Reducing features by feature engineering of Label 02

  1. Get the dataset and remove unwanted labels
  2. create a model using Random Forest before feature engineering
  3. create a model using Random KNN before feature engineering
  4. Add KNN-predicted data since it has better accuracy to CSV file
  5. Find the best k features and select
     (before selecting features check if k is enough to achieve better accuracy and finally come up with k features.)
  6. Check whether the accuracy of the selected features is enough or not using random Forester
  7. Check whether the accuracy of the selected features is enough or not using KNN
  8. Add KNN predicted data since it has better accuracy to csv file
    (do not add PCA since the test data will be reduced due to increasing the NaN data of PCAs)
