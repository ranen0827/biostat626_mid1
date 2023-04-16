# BIOSTAT 626_midterm 1
**Name**: Shushun Ren; **UM-ID**: 24284779  
**Date**: 04/14/2023

## Task 1: Binary classfication
- Read data: read the `training_data.txt` and `test_data.text`, respectively, using `read.table` function with argument `header = TRUE`;
- Recoding: the original outcome of interest `activity` should be recategorized into 0, 1, using the `ifelse` function;
- Dataset split: the training dataset can then be split into two parts, namely  `train_data1` and `test_data1`, and named the test dataset as `test_df`
- Modelling and evaluation: use the SVM algorithm with linear kernel (combined with bootstraping) to deal with the binary classification. The overall precision on the `test_data1` can be found at the `svm_l.pred` variable. 
- Prediction: we predicted the outcome (activity) on `test_df` using `predict()` function. After transforming the results to numeric values, we write these values (without headers) out to `binary_4779.txt`. 

## Task 2: Multi-class classification
- Read data: read `training_data.txt` and `test_data.txt`, separately;
- Recoding: the original outcome of interest `activity` should be recategorized into 1,2,3,4,5,6,7, using the `ifelse` function; 
- Dataset split: Same as the case in binary classification, the training dataset can be split into two parts, namely `train_data2` and `test_data2`, and named the test dataset as `test_df1`;
- Modelling and evaluation: you can use `svm()` function combined with repeated cross validation. The overall precision on the `test_data2` can be found at the `svm_r.pred` variable;
- Prediction: we predicted the outcome (activity) on `test_df1` using `predict()` function. After transforming the results to numeric values, the values (without headers) should be written into the `multiclass_4779.txt`.

