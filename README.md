# Restaurant Rating Prediction - Machine Learning Capstone

## Project Overview

This project focuses on predicting restaurant ratings using machine learning regression techniques.

## Dataset

The dataset contains restaurant-related information including ratings, reviews, restaurant names, pictures, and other attributes.

## Data Preprocessing

The following preprocessing techniques were applied:

- Data cleaning
- Categorical encoding
- Text preprocessing
- Lower casing
- Punctuation removal
- URL and digit removal
- Stopword removal
- White-space removal
- Tokenization
- Text normalization using lemmatization
- Part-of-Speech tagging
- TF-IDF vectorization
- Feature selection
- Data transformation
- Data scaling
- PCA dimensionality reduction
- Train-test splitting

## Machine Learning Models

Three regression models were implemented:

1. Random Forest Regression
2. Gradient Boosting Regression
3. Extra Trees Regression

## Final Model

After comparing the models and performing hyperparameter tuning, the Tuned Extra Trees Regression model was selected as the final model.

### Final Model Performance

- MAE: 0.50268
- MSE: 0.41497
- RMSE: 0.64418
- R² Score: 0.58364

### Best Parameters

- n_estimators: 200
- max_depth: 20
- min_samples_split: 2

## Model Explainability

Feature importance was analyzed using the Extra Trees model.

The most important PCA components included:

- PCA_Component_2
- PCA_Component_9
- PCA_Component_6
- PCA_Component_4
- PCA_Component_1

## Model Deployment Preparation

The final model was saved using Joblib and successfully loaded again to generate predictions on unseen test samples.

## Conclusion

A complete machine learning pipeline was developed for restaurant rating prediction. Multiple regression models were compared, hyperparameter tuning was performed, and the Tuned Extra Trees Regression model was selected based on its overall evaluation performance.
