# Analysis of customer statisfaction and dissatisfaction

# Project overview
This Project use Logistic Regression to classify customer under satisfied or dissatisfied, and also to discover this key component for customer
satisfaction

# Objectives

- Clean and explore the data set
- examine the customer satisfaction data
- seperate data to train and test set
- build a bimodal logistic regression model
- generate report such as accuracy, classification_report and confusion_matrix
- Identify the coefficient to get the key concept that result in satisfaction

## Installation

pip install pandas numpy matplotlib seaborn scipy statsmodels

## Run

Open:

logistic_reg.ipynb

Execute all cells.

# model Interpretation
Model Performance

The Logistic Regression model achieved an accuracy of 79%, meaning that the model correctly classified approximately 79 out of every 100 passengers as either satisfied or dissatisfied.

The model performance by class is:

Class	Precision	Recall
Dissatisfied	0.80	0.82
Satisfied	0.78	0.76
Interpretation
Precision measures how many predicted passengers in a class actually belong to that class.
Recall measures how many actual passengers in a class were correctly identified by the model.

The results indicate that the model performs slightly better at identifying dissatisfied customers than satisfied customers.

Coefficient Interpretation (Corrected)

The Logistic Regression coefficients indicate the direction and strength of influence of each feature on customer satisfaction while holding other variables constant.

Positive coefficients increase the likelihood that a customer will be classified as satisfied.

The analysis suggests that:

Inflight Entertainment
Seat Comfort
Ease of Online Booking

are among the strongest contributors to customer satisfaction.

Important: A coefficient value does not mean customer satisfaction increases by that exact amount.

For example:

If the coefficients are:

Feature	Coefficient
Inflight Entertainment	7.23
Seat Comfort	4.63
Ease of Online Booking	4.11

This means:

A one-unit increase in Inflight Entertainment increases the log-odds of customer satisfaction by 7.23.
A one-unit increase in Seat Comfort increases the log-odds of customer satisfaction by 4.63.
A one-unit increase in Ease of Online Booking increases the log-odds of customer satisfaction by 4.11.

These variables have the strongest positive influence on predicting customer satisfaction.

