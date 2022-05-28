# Autoencoders
Autoencoders for dimension reduction

## Summary

This paper evaluates the effectiveness of autoencoding for dimension reduction as a data preprocessing 
step for predicting credit card default with logistic regression.

## Results

Overall, reducing the dimensionality of the dataset with an autoencoder did not improve the F1 score of
prediction with logistic regression. From this, we can conclude this dataset was not highly dimensional 
and did not necessarily need dimension reduction for the logistic regression models to better train on.
But, the reduced logistic regression model did achieve superior recall scores under the rule based cutoff, 
approaching 100% recall. In applications like bankruptcy and default, accurately identifying cases of 
default can be the most important factor. Further, future studies could tune the hyperparameters or 
even use different types of autoencoders to potentially increase the value of dimension reduction.
