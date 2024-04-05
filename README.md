# credit-risk-classification
Module 20 Challenge

## Overview of the Analysis
The purpose of the Credit Risk analysis is to determine the creditworthiness o potential borrowers. Data was extracted from a large dataset of historical lending activity, sourced rom a peer-to-peer lending service. Using this data, I built a Logistical Regression model, split our data into Test and Train datasets, in order to train the algorithm. My model parsed through the original dataset, identifying trends and using those trends in order to calculate predictions.

I capped the model at 100 iterations, because that appeared to be the most efficient number to use, in order to cut down on processing time without sacrificing results. More iterations did not increase or decrease the prediction performance of the model. 

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model:
    * Accuracy: .99
    * Precision, Healthy Loans (0): 1.00
    * Precision, High-Risk Loans (1): .85
    * Recall, Healthy Loans (0): .99
    * Recall, High-Risk Loans (1): .91

## Summary

This model, overall, is very reliable when predicting healthy and high-risk loans. I believe the healthy loan prediction is more accurate, but both models are highly effective. I might recommend using the healthy loan predictor over the high-risk model, because there will be a better chance for borrowers to qualify for a loan. Instead of eliminating high-risk borrowers based on patterns displayed by other high-risk borrowers, lenders can use healthy loan trends as parameters instead. If a potential borrower falls within the healthy loan boundaries, it can be predicted that they are safe to lend to. This method leaves less room for error, and theoreticaly ensures that qualified borrowers won't be eliminated due to the margin of error in our model.

