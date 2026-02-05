### **House Price Prediction — Model Evaluation Report**



**Project Overview**

This project builds multiple machine learning regression models to predict house prices based on property features such as area, bedrooms, bathrooms, age, location, and property type.



The goal is to compare different regression approaches and identify the best performing model.



**Dataset Description**

The dataset contains 300 property records with the following features:



\- Area (sq ft)

\- Bedrooms

\- Bathrooms

\- Age

\- Location

\- Property Type

\- Price (Target Variable)



Categorical variables were encoded using Label Encoding.



**Methodology**



**### Data Preprocessing**

\- Checked missing values

\- Encoded categorical variables

\- Dropped non-numeric identifiers

\- Selected relevant features

\- Train-test split (80/20)



**### Models Implemented**

1\. Linear Regression

2\. Polynomial Regression

3\. Decision Tree Regressor

4\. Random Forest Regressor



**## Evaluation Metrics**



**### MAE — Mean Absolute Error**

Average absolute difference between actual and predicted prices.



**### MSE — Mean Squared Error**

Average squared difference between actual and predicted values.



\#**## R² Score**

Measures how well the model explains price variance.

Range: (-∞ to 1). Higher is better.



**## Results Summary**



*| Model | R² Score |*

*| Linear Regression | 0.70 |*

*| Decision Tree | 0.95 |*

*| Random Forest | 0.97 |*



*(Random Forest achieved the best performance.)*



**## Feature Importance Insights**

Random Forest feature importance analysis shows:



\- Area is strongest predictor

\- Location has major influence

\- Property Type impacts pricing

\- Age has moderate effect



**## Visualization**

A scatter plot of predicted vs actual prices was generated to visually validate model accuracy.



File: predictions\_vs\_actual.png



**## Conclusion**

Tree-based models outperformed linear models due to their ability to capture non-linear patterns. Random Forest provided the highest predictive accuracy and most reliable results.



**Future improvements:**

\- More data

\- One-hot encoding

\- Hyperparameter tuning

\- Cross-validation



