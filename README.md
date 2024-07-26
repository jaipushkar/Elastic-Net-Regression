# Elastic-Net-Regression

**Elastic Net Regression with Python**
This script demonstrates the use of Elastic Net regression for fitting a model to data. Elastic Net is a regularized linear regression model that combines the penalties of Lasso and Ridge regression to improve model performance and stability.

**Overview**
**Data Generation**
**Features:** X is generated as 2 - 3 * np.random.normal(0, 1, 100), creating a normal distribution.
**Target:** Y is generated using a polynomial function with added noise to simulate real-world data.

**Model Training**
**Elastic Net:** Combines both L1 (Lasso) and L2 (Ridge) penalties to improve the regression model.
**Hyperparameters:** alpha controls the strength of regularization, and l1_ratio balances the contributions of L1 and L2 penalties.
Evaluation
**Mean Squared Error (MSE):** Measures the average squared difference between predicted and actual values for both training and testing datasets.

**Visualization**
**Training and Testing Data:** Scatter plots for visualizing the actual data points.
**Model Fit:** A line plot showing the Elastic Net regression fit.

**Code Explanation**
**Data Generation:**
Generates synthetic data for demonstration purposes.

**Train-Test Split:**
Splits the dataset into training and testing sets for model evaluation.

**Model Initialization and Training:**
Initializes the Elastic Net model with specified hyperparameters.
Trains the model on the training data.

**Prediction and Evaluation:**
Makes predictions on both training and testing sets.
Calculates and prints the Mean Squared Error for both sets.

**Visualization:**
Plots the training and testing data points.
Plots the Elastic Net regression fit line over the data.
