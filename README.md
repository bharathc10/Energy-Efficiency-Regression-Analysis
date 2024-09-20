# Energy-Efficiency-Regression-Analysis

This project implements a custom linear regression model to predict energy efficiency based on various features using gradient descent. The dataset used for this analysis is the Energy Efficiency Dataset, which includes two target variables: Heating Load (Y1) and Cooling Load (Y2).

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Results](#results)
- [License](#license)

## Project Overview
The goal of this project is to demonstrate a thorough understanding of regression analysis, data preprocessing, and model evaluation techniques. The project includes:
- Data loading and preprocessing (scaling and outlier detection).
- Custom implementation of gradient descent for linear regression.
- Regularization techniques to improve model performance.
- Evaluation metrics: Mean Squared Error (MSE) and R² scores.

## Dataset
The Energy Efficiency Dataset is sourced from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Energy+efficiency). It contains features related to energy efficiency in buildings and the two target variables: Heating Load (Y1) and Cooling Load (Y2).

## Methodology
1. **Data Loading and Exploration**: The dataset is loaded using Pandas, and exploratory data analysis (EDA) is performed to understand the structure and quality of the data.
2. **Data Preprocessing**: The features are scaled using a custom scaler to ensure uniformity across different ranges.
3. **Model Implementation**: A custom linear regression model is implemented using gradient descent, with L2 regularization to mitigate overfitting.
4. **Model Evaluation**: The model's performance is evaluated using MSE and R² scores, and results are visualized through scatter plots.

## Results
The model's performance for Heating Load (Y1) and Cooling Load (Y2) is summarized as follows:

- **Heating Load (Y1)**:
  - MSE: 0.0965
  - R²: 0.9035

- **Cooling Load (Y2)**:
  - MSE: 0.1290
  - R²: 0.8710

The visualizations indicate a consistent correlation between predicted and actual values, suggesting the model performs well.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

