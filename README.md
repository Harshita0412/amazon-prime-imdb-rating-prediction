# Amazon Prime Video IMDb Rating Prediction

## Project Overview
This project focuses on predicting IMDb ratings of movies and TV shows using content-related metadata from the Amazon Prime Video dataset.

## Machine Learning Algorithm
- XGBoost Regressor

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- XGBoost
- NLTK
- TF-IDF

## Project Workflow
1. Data Cleaning and Preprocessing
2. Exploratory Data Analysis
3. Textual Data Preprocessing
4. Feature Engineering and Selection
5. Data Transformation
6. Model Training
7. Hyperparameter Optimization using RandomizedSearchCV
8. Model Evaluation

## Final Model Performance

| Metric | Score |
|---|---:|
| MAE | 0.7788 |
| MSE | 0.9972 |
| RMSE | 0.9986 |
| R² Score | 0.4268 |

## Hyperparameter Optimization
RandomizedSearchCV with 5-fold cross-validation was used to optimize the XGBoost Regressor.

## Project Outcome
The tuned XGBoost model achieved an R² score of approximately 0.4268 on the test dataset.

The project demonstrates how content metadata can be used to estimate IMDb ratings through machine learning.
