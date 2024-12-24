# Happiness Prediction Project

This project aims to predict happiness scores (Life ladder) based on various factors such as GDP, social support, freedom, and more.

## Steps:

1. **Data Exploration**: 
   - Summarizing the dataset, identifying continuous and categorical features.
   - Handling missing data and special cases.

2. **Statistical Summary & Visualization**: 
   - Displaying statistical values and visualizations (e.g., histograms).
   - Analyzing distributions and identifying patterns.

3. **Relationship Analysis**:
   - Computing Pearson Correlation Coefficient and generating scatter plots to analyze relationships between attributes and the target.

4. **Data Splitting**: 
   - Splitting the dataset into training and testing sets (75% training, 25% testing) ensuring the test set is representative.

5. **Model Training**:
   - Training a **Linear Regression** model using both a closed-form solution and **Stochastic Gradient Descent (SGD)**.
   - Applying **Ridge**, **Lasso**, and **Elastic Net** regularization to prevent overfitting.

6. **Polynomial Regression**: 
   - Training a polynomial regression model and evaluating overfitting/underfitting.

7. **Prediction & Evaluation**: 
   - Using the trained model to make predictions and evaluate performance with appropriate metrics.

8. **Future Work**: 
   - Exploring further improvements like fine-tuning hyperparameters and adding more features.
