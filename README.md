# Fraud-Detection
Logistic regression model using Scikit-learn to predict fraudulent transactions

# Intro
The PwC global economic crime survey of 2016 suggests that approximately 36% of organizations experienced economic crime. Therefore, there is definitely a need to solve the problem of credit card fraud detection. The task of fraud detection often boils down to outlier detection, in which a dataset is scanned through to find potential anomalies in the data. In the past, this was done by employees  which checked all transactions manually. With the rise of machine learning, artificial intelligence, deep learning and other relevant fields of information technology, it becomes feasible to automate this process and to save some of the intensive amount of labor that is put into detecting credit card fraud. In this assignment, we'll train a model with pandas, seaborn and scikit-learn to create a fraud detection classifier.

# About the project
I  build  a logistic regression model using Scikit-learn to predict fraudulent transactions by training it on  kaggle dataset
Dataset can be downloaded from here https://www.kaggle.com/c/ieee-fraud-detection/data. 

I create different visualization of the data using the seaborn library.The data consists of 28 variables (V1, …, V28), an “Amount” field a “Class” field and the “Time” field.We do not know the exact meanings of the variables (due to privacy concerns).

I split the data into train and test set.

I normalize the data by subtract the mean and divide by the standard deviation.

As a model I used Logistic Regression form sklearn library.

I fit the model with the train set. 

I evaluate the models and show the results.

I was inspired by this article https://www.data-blogger.com/2017/06/15/fraud-detection-a-simple-machine-learning-approach/


# Installation
Clone the repo

https://github.com/lupa123/Fraud-Detection.git

Download the kaggle dataset and put it in the project folder. https://www.kaggle.com/c/ieee-fraud-detection/data

I uploaded a notebook document when I trained and test a logistic regresion model with this dataset.
