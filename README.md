# Credit Risk Classification Challenge
This repository contains my homework for Module 20.

The task was to build, train and evaluate a model that can identify the creditworthiness of borrowers. 

## Attachments
In this repository, you will find:
- a folder called "Credit_Risk": In this folder, you will find the dataset provided for this homework and the code I have written to build, train and evaluate the Logistic Regression Model.

## Result

Furthermore, I have been asked to write a Credit Risk Analysis Report with the outcome.
Please see below


### Report: Logistic Regression Machine Learning to predict creditworthiness of borrowers 
#### Overview of the Analysis

The purpose of this analysis was to develop a machine learning model, that allow us to predict the creditworthiness of a borrower based on financial information.

The dataset provided, to train the model, contained various parameters including: loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, total debt, and loan status. The loan status was categorized as either a healthy loan (0) or a high-risk loan (1).

#### The stages of the machine learning process involved

- Data Exploration: Gaining an understanding of the dataset and examining the distribution of loan status values;
- Model Training and Evaluation: Splitting the data into training and testing sets, training the model on the training set, and evaluating its performance on the testing set;
- Model Optimization: Exploring functionality, such as resampling methods, to enhance model performance.

#### Result

Machine Learning Model 1: Logistic Regression
- Accuracy: The logistic regression model achieved an accuracy score of 0.9924, indicating that approximately 99.24% of the instances were correctly classified;
- Precision and Recall: The precision score for class 0 (healthy loan) was 100%, indicating that all instances predicted as healthy loans were correctly classified. For class 1 (high-risk loan), the precision score was 87%, suggesting that 87% of instances predicted as high-risk loans were actually high-risk loans. The recall score for class 0 was 100%, indicating that all actual healthy loans were correctly identified, while the recall score for class 1 was 89%, indicating that 89% of actual high-risk loans were correctly identified.

Machine Learning Model 2: Logistic Regression with Resampling
- Accuracy: After applying RandomOverSampler, the model achieved an improved accuracy score of 0.9945, indicating approximately 99.45% of the instances were correctly classified;
- Precision and Recall: For both class 0 and class 1, the precision, recall, and F1-scores were all very high, at 99% and above. This indicates that the model performed well in predicting both healthy loans and high-risk loans, with balanced precision and recall scores for both classes.

#### Summary

Based on the analysis, both models demonstrated high accuracy, precision, and recall scores. The logistic regression model with resampling performed slightly better, achieving a higher accuracy score of 0.9945 compared to 0.9924 for the initial logistic regression model.

Considering the purpose of the model, which is to correctly identifying both healthy loans and high-risk loans. The logistic regression model with resampling appears to be the best choice. 

