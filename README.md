# Sales-predictor


Description:
This project demonstrates the use of linear regression to predict sales based on advertising spending on TV. It utilizes Python libraries such as pandas, numpy, matplotlib, seaborn, and scikit-learn to perform the following steps:

Data Import and Exploration:

The project starts by reading a dataset (presumably containing TV advertising spending and sales data) using pandas.
The dataset is explored to understand its structure and contents.
Data Preparation:

The feature (X) and target (y) variables are defined. In this case, TV advertising spending is used as the feature, and sales are the target.
The dataset is split into training and testing sets using train_test_split from scikit-learn.
Model Training:

A Linear Regression model is created and trained on the training data using scikit-learn's LinearRegression.
Model Evaluation:

The model's performance is evaluated using various metrics, including mean absolute error (MAE), mean squared error (MSE), root mean squared error (RMSE), and R-squared (R²) score.
These metrics provide insights into how well the model fits the data and its predictive accuracy.
Visualization:

The project includes data visualization using matplotlib and seaborn to illustrate the relationship between TV advertising spending and sales.
A scatter plot with a line of best fit is created to visualize the regression model's predictions.
Key Components:

Importing and exploring the dataset.
Preprocessing and splitting the data.
Training a Linear Regression model.
Evaluating the model using regression metrics.
Creating data visualizations for insights.
Summary:
This project demonstrates the use of linear regression as a simple but effective tool for sales prediction based on TV advertising spending. It highlights key steps in the machine learning workflow, from data preparation to model training and evaluation. The project also emphasizes the importance of visualizing data and model predictions to gain a better understanding of the relationship between variables
