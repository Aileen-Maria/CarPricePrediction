# Car Price Prediction using Machine Learning

## Overview
This project focuses on predicting car prices using various machine learning techniques. The primary goal is to identify key factors affecting car pricing in the US market and build an accurate predictive model using multiple regression methods. The analysis is performed in a Jupyter Notebook.

## Problem Statement
The objective is to analyze a dataset containing 205 car entries with 26 features and develop models to predict car prices. Models are evaluated using R² Score, Mean Squared Error (MSE), and Mean Absolute Error (MAE) to determine the most reliable predictor.

## Dataset
- **Description:** The dataset includes features related to car specifications such as engine details, dimensions, fuel type, etc.
- **Preprocessing:** Data cleaning, encoding of categorical variables, and scaling of numerical features have been performed.

## Methodology
The project follows these steps:
1. **Data Preprocessing:**  
   - Data cleaning and transformation.
   - Extraction of features (e.g., car brand from the CarName field).
   - Encoding categorical variables using one-hot encoding.
2. **Model Implementation:**  
   - Linear Regression
   - Decision Tree Regressor
   - Random Forest Regressor
   - Gradient Boosting Regressor
   - Support Vector Regressor (SVR)
3. **Model Evaluation:**  
   - Comparison based on R² Score, MSE, and MAE.
4. **Feature Importance Analysis:**  
   - Identification of key features influencing car prices.
5. **Hyperparameter Tuning:**  
   - Optimization of the best-performing model (Random Forest Regressor).

## Results
| Model                         | R² Score   | MSE         | MAE       |
|-------------------------------|------------|-------------|-----------|
| **Linear Regression**         | -3.94e+23  | 3.11e+31    | 8.71e+14  |
| **Decision Tree Regressor**   | 0.9069     | 7.35e+06    | 1.78e+03  |
| **Random Forest Regressor**   | 0.9586     | 3.27e+06    | 1.29e+03  |
| **Gradient Boosting Regressor** | 0.9242   | 5.99e+06    | 1.71e+03  |
| **Support Vector Regressor**    | -0.0998  | 8.68e+07    | 5.70e+03  |

**Conclusion:**  
The **Random Forest Regressor** is the best performing model, with the highest R² Score (0.9586) and the lowest error metrics (MSE: 3.27e+06, MAE: 1.29e+03), indicating the most accurate and reliable predictions.

## Required Libraries

The project requires the following libraries:

- **pandas**: For data manipulation and analysis.
- **numpy**: For numerical computations.
- **scikit-learn**: For building and evaluating machine learning models.
- **matplotlib**: For data visualization.
- **seaborn**: For statistical data visualization.
- **jupyter**: For interactive development and analysis.

## Installation & Usage

Since this repository is managed via the GitHub web interface, you can simply:

1. **Download the Repository:**  
   - Click the **"Code"** button on GitHub and select **"Download ZIP"**.
   - Extract the files to your desired location.

2. **Install Dependencies:**  
   Ensure you have Python 3.x installed, then install the required packages:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn jupyter
