# Diabetes-Analysis-and-Prediction

Welcome to the Predicting Diabetes with Machine Learning project! We're thrilled to have you here. In this project, we embark on a journey to predict the onset of diabetes using the power of machine learning. If you're passionate about data science, health analytics, or simply want to explore the world of predictive modeling, you're in for an exciting ride!

## Project Overview

In this project, we work with the Pima Indians Diabetes dataset, which includes various health indicators like Pregnancies, Glucose, Blood Pressure, Skin Thickness, Insulin, BMI, Diabetes Pedigree Function, and Age. Our mission is to train a logistic regression model to accurately predict the likelihood of an individual developing diabetes.

## Key Steps

### 1. Data Exploration

We kick things off by loading the dataset and getting a feel for the data. This involves:

- **Data Cleaning**: Checking for missing values and duplicates to ensure a clean dataset.
- **Visualization**: Using heatmaps, boxplots, and histograms to understand data distributions and relationships between features.

### 2. Correlation Analysis

Understanding feature relationships is crucial. We use a correlation matrix to visualize how different features interact and which ones are strongly correlated with the target variable, Outcome.

### 3. Handling Outliers

Outliers can skew our model’s performance. We tackle this by implementing the interquartile range (IQR) method to replace outlier values with the mean of their respective columns.

### 4. Model Training

Time to build our model! We:

- **Split the Data**: Divide the dataset into training and testing sets.
- **Scale the Features**: Normalize the data for better performance.
- **Train the Model**: Use TensorFlow to create and train a logistic regression model, monitoring its performance with a custom callback function.

### 5. Model Evaluation

After training, we evaluate our model on the test set and visualize its performance through loss and accuracy plots. This helps us understand how well our model is performing and where we can improve.

## Insights and Learnings

Throughout this project, we gain valuable insights into the factors that drive diabetes onset. Key learnings include:

- The importance of thorough data preprocessing and feature engineering.
- How different health indicators influence diabetes risk.
- The performance of logistic regression in predicting diabetes onset.

## Conclusion

The Predicting Diabetes with Machine Learning project is an insightful dive into the realm of data science and healthcare. We explore the dataset, preprocess the data, build a robust model, and even allow for user input predictions. It's a comprehensive journey that showcases the power of machine learning in health analytics.

Whether you're a data science enthusiast, a health professional, or someone keen on learning more about machine learning, this project offers valuable insights and hands-on experience.







