# Heart-Disease-Predictor
Heart Disease Predictor project. 

This project uses the Heart Disease dataset from Kaggle. Here is our presentations [slides](https://www.canva.com/design/DAFdotrY1hA/EVLGTds1KHDa02-J5L70yg/edit) and [video](https://drive.google.com/file/d/1y1P5ds_2jYjox3cuqYuXXuRj2oG-4_Mp/view). For a complete walkthrough of the project, refer to the following jupyter notebooks in order form:

Exploratory Data Analysis & Data Preparation
Machine Learning
Data-Driven Insights & Recommendations

# Problem Defintion
Are we able to predict if a patient will suffer from heart disease in patients based on their medical conditions?
Which condition (variable) will be the most important in predicting whether a patient is likely to develop heart disease?

# Models Used
- K-Nearest Neighbours
- Decision Tree Classifier
- Logistic Regression
- Random Forest Classifier
- Neural Networks

# Summary and Conclusion

1. The neural network model was the most accurate model in predicting whether a person has heart disease.
2. "Thal" is the most important variable in predicting heart disease as this variable is deemed the most important by 2 Machine Learning models.
3. The Logistic Regression model's most significant feature was "sex" but our exploratory data analysis indicated no relationship between sex and heart disease. Thus, the coefficient feature importance method may not be entirely accurate.
4. It is possible to predict if a person will suffer from heart disease & identify the most important factor using Machine Learning. ML models aid in early detection by identifying factors in patient data that can cause heart disease. For example, a patient with "Thal" type 1 and type 3 has a higher likelihood of heart disease, enabling doctors to diagnose and treat the condition earlier.
5. To enhance accuracy in predicting the primary factor in determining heart disease, a dataset comprising medical records, lab results, lifestyle factors, and genetic data could have been used. This approach would have enabled the models to capture a wider range of risk factors

# What we learned from this project 

1. Random Forest Classifier, Logistic Regression, K-Nearest-Neighbours, and Neural Networks
2. Finding the optimal value of K for the KNN model
3. Finding the optimal depth for the Decision Tree Classifier
4. Importance of scaling the data using Standard Scaler prior to Machine Learning
5. Using the interactive library of Plotly for data visualization
6. Label encoding. The necessity of having our target variable to be encoded with the values of 0 and 1 for the absence and presence of heart disease instead of "No" and "Yes".
7. Permutation feature importance method to deduce the most important feature in the KNN model
8. Coefficient feature importance method to deduce the most important feature in the Logistic Regression model
9. Using Github as a tool for collaboration

















