## University of Essex 
## School of Computer Science and Electronic Engineering 
## CE802 Machine Learning

## Assignment: Design and Application of a Machine Learning System for a Practical Problem

## Assignment objectives

Prof. Luca Citi
Individual Assignment
This document specifies the coursework assignment to be submitted by students taking CE802. Aims of this assignment are: 

a) to learn to identify machine learning techniques appropriate for a particular practical problem; and 
b) to undertake a comparative evaluation of several machine learning procedures when applied to the specific problem.

## Part 1(P2)

## a) Investigate the performance of a number of machine learning procedures on this dataset :

Using the data in the file CE802_P2_Data.csv contained in the CE802_P2_Data.zip archive, you are required to perform a comparative study of the following machine learning proce- dures:

* a Decision Tree classifier;
* at least two more ML technique to predict if the hotel will make a profit.

You will notice that one of the features is missing for some of the instances. You are therefore required to deal with the problem of missing features before you can proceed with the prediction step. As a baseline approach you may try to discard the feature altogether and train on the remaining features. You are then encouraged to experiment with different imputation methods.
The company uses Python internally and therefore Python with scikit-learn is the required language and machine learning library for the problem. For this task, you are expected to submit a Jupyter Notebook called CE802_P2_Notebook.ipynb containing the Python code used to perform the comparative analysis and produce the results, as well as the code used to perform the predictions described in task “b” below.

## b) Prediction on a hold-out test set :

An additional dataset, CE802_P2_Test.csv, is provided inside the CE802_P2_Data.zip archive. Binary outcomes are withheld for this test set (i.e. the “Class” column is empty). In this second task you are required to produce class predictions of the records in the test set using one approach of your choice among those tested in task “a” (for example the one achieving the best performance). These data must not be used other than to test the algorithm trained on the training data.
As part of your submission you should submit a file called CE802_P2_Test_Predictions.csv in CSV format, which must be identical to CE802_P2_Test.csv except that the missing class is replaced with the output predictions obtained using your chosen approach. This second task will be marked based on the prediction accuracy on the test set.

## Part 2(P3)

## a) Investigate the performance of a number of machine learning procedures on this dataset :

Using the data in the file CE802_P3_Data.csv contained in the CE802_P3_Data.zip archive, you are required to perform a comparative study of the following machine learning proce- dures:

* Linear Regression;
* at least two more ML technique to predict the profit.

This company too uses Python internally and therefore Python with scikit-learn is the required language and machine learning library for the problem. For this task, you are expected to submit a Jupyter Notebook called CE802_P3_Notebook.ipynb containing the Python code used to perform the comparative analysis and produce the results as well as the code used to perform the predictions described in task “b” below.

## b) Prediction on a hold-out test set :

An additional dataset, CE802_P3_Test.csv, is provided inside the CE802_P3_Data.zip archive. Target values are withheld for this test set (i.e. the “Target” column is empty). In this second task you are required to produce predictions of the records in the test set using one approach of your choice among those tested in task “a” (for example the one achieving the best performance). These data must not be used other than to test the algorithm trained on the training data.

As part of your submission you should submit a file called CE802_P3_Test_Predictions.csv in CSV format, which must be identical to CE802_P3_Test.csv except that the missing “Target” column is replaced with the output predictions obtained using your chosen approach. This second task will be marked based on the root mean squared error on the test set.


