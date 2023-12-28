# Apple Stock Price Forecasting with Machine Learning

## Overview

This project leverages machine learning techniques to predict Apple stock prices based on historical data. The dataset used for this project is sourced from Kaggle and was published by [Rafsun Ahmad](https://www.kaggle.com/rafsunahmad).

## Dataset

- **Dataset Link:** [Apple Stock Price Dataset](https://www.kaggle.com/datasets/rafsunahmad/apple-stock-price)
- **Publisher:** [Rafsun Ahmad](https://www.kaggle.com/rafsunahmad)
- **Author:** Suleyman Yahaya

## Project Steps

1. **Data Import and Exploration:**
   - Imported necessary libraries to facilitate data analysis.
   - Loaded the dataset into a Pandas DataFrame for exploration.
   - Explored and visualized the data to gain insights into stock price patterns and trends.

2. **Feature Selection and Data Splitting:**
   - Selected relevant features ('Open', 'High', 'Low', 'Volume') and the target variable ('Close') for modeling.
   - Split the dataset into training and testing sets to assess model performance on unseen data.

3. **Modeling:**
   - Implemented a linear regression model for forecasting stock prices.
   - Trained the model on historical data to capture patterns and relationships.
   - Utilized the trained model to make predictions on the test set.

4. **Evaluation:**
   - Evaluated the model using key metrics:
     - **Mean Squared Error (MSE):** A measure of the average squared difference between actual and predicted values. Lower values indicate better model performance.
     - **Mean Absolute Error (MAE):** A measure of the average absolute difference between actual and predicted values.
     - **R-squared:** Indicates the proportion of variance in the dependent variable explained by the independent variables. Close to 1 indicates a good fit.

5. **Results:**
   - Achieved a low MSE and MAE, indicating accurate predictions.
   - Observed a high R-squared, suggesting that the model explains a significant portion of the variance in stock prices.

## How to Use

To replicate or extend this project, follow these steps:
1. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/rafsunahmad/apple-stock-price).
2. Use the provided Jupyter Notebook or adapt the code for your preferred environment.

Feel free to explore, modify, and share your insights!

## Acknowledgments

- Special thanks to Rafsun Ahmad for sharing the dataset on Kaggle.

