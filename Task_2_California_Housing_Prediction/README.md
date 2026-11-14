# Task 2: Real Estate Housing Price Prediction

## Project Overview
This project focuses on predicting house prices using Machine Learning regression algorithms. The California Housing Dataset is used to analyze housing-related features and build predictive models.

Three regression algorithms are implemented and compared: Linear Regression, Ridge Regression (L2 Regularization), and Lasso Regression (L1 Regularization).

The objective is to evaluate model performance and identify the most effective regression model using standard evaluation metrics.

## Objectives
- Load and explore the California Housing Dataset.
- Perform Exploratory Data Analysis (EDA).
- Identify and handle missing values.
- Create interaction features.
- Analyze multicollinearity among features.
- Standardize input features.
- Train Linear, Ridge, and Lasso Regression models.
- Optimize regularization parameters using GridSearchCV.
- Compare models using RMSE, MAE, and R² Score.
- Visualize actual versus predicted values and residual errors.

## Dataset Information
**Dataset:** California Housing Dataset  
**Source:** Scikit-learn built-in dataset  
**Total Records:** 20,640  
**Input Features:** 8  
**Target Variable:** `MedHouseVal`

### Features
- MedInc – Median income
- HouseAge – Median house age
- AveRooms – Average number of rooms
- AveBedrms – Average number of bedrooms
- Population – Population
- AveOccup – Average household occupancy
- Latitude – Geographic latitude
- Longitude – Geographic longitude

## Machine Learning Algorithms

### 1. Linear Regression
A baseline regression model used to establish the relationship between input features and house prices.

### 2. Ridge Regression (L2)
Applies L2 regularization to reduce the impact of large model coefficients and help control overfitting.

### 3. Lasso Regression (L1)
Applies L1 regularization and can reduce less important feature coefficients to zero.

GridSearchCV is used to find suitable regularization parameters for Ridge and Lasso Regression.

## Model Evaluation

The models are evaluated using:

| Metric | Purpose |
|---|---|
| RMSE | Measures prediction error, penalizing larger errors |
| MAE | Measures average absolute prediction error |
| R² Score | Measures the proportion of target variance explained by the model |

### Best Model Result

| Metric | Lasso Regression |
|---|---:|
| RMSE | 0.7411 |
| MAE | 0.5305 |
| R² Score | 0.5808 |

**Best Performing Model: Lasso Regression**

Lasso Regression achieved the lowest RMSE among the three evaluated models in this experiment.

## Visualizations
The project includes:
- Target variable distribution.
- Feature distribution histograms.
- Feature correlation heatmap.
- Actual vs Predicted values plot.
- Residual distribution plots.
- Residual scatter plots.

## Technologies Used
- Python
- Google Colab
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels

## Project Structure

```text
Task_2_California_Housing_Prediction/
│
├── README.md
│
├── Notebook/
│   └── Task_2_California_Housing_Price_Prediction.ipynb
│
└── Results/
    ├── Model_Comparison.csv
    ├── Actual_vs_Predicted.png
    └── Residual_Distribution.png
```

## Conclusion
This project demonstrates the application of regression techniques for housing price prediction. Linear Regression, Ridge Regression, and Lasso Regression were trained and evaluated using the California Housing Dataset.

Among the three models, Lasso Regression achieved the best performance in this experiment, with an RMSE of 0.7411, MAE of 0.5305, and R² Score of 0.5808.

The experiment highlights the importance of feature engineering, feature standardization, regularization, hyperparameter optimization, and model evaluation in developing machine learning regression models.

---

**Project:** Datheon Machine Learning & Data Science Internship  
**Task:** Task 2 – Real Estate Housing Price Prediction
