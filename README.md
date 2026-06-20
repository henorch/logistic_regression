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
at accuracy score of 79%, the model is able to predict 79 out of every 100 passenger, 0.80 precision and 0.82 Recall for our dissatisfied customer and 0.78 Precision and 0.76 recall for our satisfied customers, this shows the True positive and False Negative accuracy of the model

The coefficient of the model shows that Seat comfort, Inflight entertainment, and Ease of Online Booking are major contributor to customer satisfaction, while holding other variables constant. Seat number can increase satisfaction by 4.63, Inflight entertainment can increase it by 7.23 and Ease of online booking can increase satisfaction by 4.11
