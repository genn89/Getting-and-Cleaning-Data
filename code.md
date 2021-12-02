Code Book
================

The run\_analysis.R script cointains the elaboration for data
preparation, following the main steps as requested by the course
project’s definition.

## Step 1

The dataset has been downloaded and named UCI HAR Dataset.

then, we have extracted the following .txt file:

1.  Features: list of all features
2.  Activities: links the class labels with their activity name  
3.  Subject\_test: list of subject choosen as test set
4.  x\_test: test set
5.  y\_test: test labels
6.  Subject\_train: list of subject choosen as training set
7.  x\_train: training set
8.  y\_train: training labels

## Step 2

Merges the training and the test sets to create one data set

Using cbind() function we have put together first y\_train,
subject\_train, x\_train and y\_test, subject\_test, x\_test. Then we
have merged all.

## Step 3

As requested, we have extracts from previous dataset the following
measurements: mean and standard deviation.

Then, we have renamed the descriptive activities.

## Step 4

We have created one more dataset, starting from the TidyData, sumarizing
the means of each variable for each activity and each subject.
