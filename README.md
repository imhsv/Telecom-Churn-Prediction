# Telecom-Churn-Prediction
# Introduction
>This project has applied Machine Learning and Deep Learning techniques to analyse and predict the Telecom churn prediction. Our task is to build a classification model using the dataset.

# Company
WeConnect - ![churn](https://user-images.githubusercontent.com/114226899/226097789-cbf28d4f-e71c-4308-847c-1e5d72ca7761.png)

 It is a Telecom Service Provider.
>The company has started facing high churn rate due to rapid development in technology and the emerging new competitors in the market.
>The objective is to use the model to take further actions for preventing customers to churn.
>They will have to offer something to their customers so they stick around, example - a promo, discount, loyalty program etc.

# Current Scenario

>Till now they have been using traditional ways which now have become a problem to handle due to human interventions.
>They have a detailed history of their customers and are looking for an automated solution to identify the likeliness of customer churning from using their services.

![cc img](https://user-images.githubusercontent.com/114226899/226098173-d352d979-f0ce-49cc-87d8-e901291366a3.jpeg)

# The company suffers from the following problems:

>Due to the boom in the telecom industry with 4G technology, it has become a pain in the neck for the company to retain their customers.
>They are in the middle of setting up more cell sites on the 4G network to improve their 4G services.
>It is plausible for customers to choose 4G services over 3G services due to benefits of cost, speed, latency etc.

# My Role

>The data have datasets of past customers and their status (Churn: Yes or No)
>Task is to build a classification model using the dataset.
>Only the need to build the best possible model.

# Data 

[Data_Train](https://github.com/imhsv/Telecom-Churn-Prediction/blob/main/Churn_train.csv)
[Data_Test](https://github.com/imhsv/Telecom-Churn-Prediction/blob/main/Churn_test.csv)

>The dataset is divided into two parts: Train and Test sets.

Train Set:
>The train set contains 5634 rows and 21 columns.
>The last column Churn is the target variable.

Test Set:
>The test set contains 1409 rows and 20 columns.
>The test set doesn’t contain the Churn column.
>It needs to be predicted for the test set.

# Analysis and Model Evaluation
> Its all works done in Jupyter notebooks.
> Best model is Xgboost classifier with 83.597 % accuracy score and 	83.879 % F1 Score.
[Data Science](https://github.com/imhsv/Telecom-Churn-Prediction/blob/main/telecomeChurn.ipynb)

# Software
All the analysis are done by using python 3.6 and others usefull libraries .
