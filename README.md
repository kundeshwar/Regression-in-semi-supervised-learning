# Regression-in-semi-supervised-learning
This project is a demonstration of regression in semi-supervised learning using Python. Semi-supervised learning is a machine learning technique that deals with partially labeled data.
## Introduction
This project is a demonstration of regression in semi-supervised learning using Python. Semi-supervised learning is a machine learning technique that deals with partially labeled data. It is a combination of supervised learning and unsupervised learning, where some data is labeled, and some are not.

Regression is a technique that is used to estimate the relationship between two or more variables. In this project, we will use linear regression and lasso regression to estimate the relationship between the car's selling price and its features.

## Installation
To run this project, you need to have Python installed on your machine. You can download and install Python from the official website python.org.

To install the required libraries, run the following command in your terminal:

**Copy code**<br>
```
pip install pandas matplotlib seaborn scikit-learn
```
## Usage
To run the project, open the regression_in_semi_supervised_learning.py file in your Python IDE or text editor and run the file. The code will load the data from the CSV file, preprocess it, split the data into training, test, and unlabelled data, train the model on the labelled data, predict the labels for the unlabelled data, and then train the model on the complete dataset. The code will also evaluate the model's performance using R-squared error and plot the actual prices against the predicted prices.

## Data
The data used in this project is the car data from Kaggle. The dataset contains various features of cars like car name, year, selling price, and other features that affect the selling price, such as the number of previous owners, fuel type, and transmission. The dataset contains 301 rows and 9 columns.

## Conclusion
In this project, we have demonstrated how to use regression in semi-supervised learning to estimate the relationship between the car's selling price and its features. We have used linear regression and lasso regression to train the model on the labelled data, predict the labels for the unlabelled data, and then train the model on the complete dataset. We have also evaluated the model's performance using R-squared error and plotted the actual prices against the predicted prices.
