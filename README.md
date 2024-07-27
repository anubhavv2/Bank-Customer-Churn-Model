# Bank-Customer-Churn-Model

This project aims to predict customer churn in a bank using various classification algorithms and visualize the results. 

## Objective
The objective is to develop a model that predicts whether a customer will churn (leave the bank) based on their profile and account activities.

## Data Source
The dataset used for this project is from the YBI Foundation's GitHub repository:
[Bank Churn Modelling Dataset](https://github.com/YBIFoundation/Dataset/raw/main/Bank%20Churn%20Modelling.csv)

## Steps

### Import Libraries
The following libraries are used in this project:
- pandas
- numpy
- matplotlib
- seaborn
- imblearn


### Data Preprocessing
Remove unwanted columns and encode categorical variables.

### 5. Data Visualization
Plot histograms and heatmaps to understand the data distribution and correlations.

### 6. Model Training
Split the data into training and testing sets, standardize the data, and train two classification models: Logistic Regression and Random Forest.

### 7. Prediction
Make predictions using the Random Forest model.

## Results
The Random Forest classifier performs better than the Logistic Regression model. 

## Conclusion
This project demonstrates how to preprocess data, train classification models, and evaluate their performance in predicting customer churn. The Random Forest model showed higher accuracy and better performance metrics compared to the Logistic Regression model.

## Acknowledgements
- YBI Foundation for providing the dataset.
