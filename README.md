# Module 20 Report

## Overview

* The purpose of the analysis is creating a Logistic Regression Model to predict healthy vs high risk loans ( a loan that is likly to be paid off in full without defalut) vs. a risky loan (where the borrower might fail to make the payment in its entirety).
* The significance here is that while healthy loans would be paid off without issue, a high risk loan would be significantly more likely to run into problems with payment. A model that could predict these with high accuracy would naturally be very valuable
* To create this model, dataset 'lending_data.csv' was loaded in and analyzed
* After analysis was conducted, the data was split into training and testing using the sklearn model
* This is when the Logistic Regression model comes in to determine our results

## Results

### LogisticRegression Model
  * Model was 99% accurate in predicting low risk loans and 91% accurate in predicting high risk loans
  * All of the accuracy and F1-score readings came back over 90% except for the high risk loans F1-score which just missed that mark at 88%

## Summary

* Based on the results, it is clear that the model is very accurate accross the board and thus I would reccomend it
* One area of concern/improvement would be the 13% false positive rate. It's not high enough for me to not endorse the model, but it certainly shouldn't be overlooked