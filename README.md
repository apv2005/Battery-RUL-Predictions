# Battery-RUL-Predictions
## Overview
The notebook performs the following functions:
 - **Data Exploration & Cleaning:** Uses Pandas, NumPy, and visualization libraries such as Matplotlib, Seaborn, and Plotly to perform exploratory data analysis and clean the battery dataset.
- **Feature Engineering:** Prepares the data for modeling by selecting relevant features and applying transformations.
- **Modeling:** Experiments with multiple machine learning algorithms including:
  - Linear Regression
  - K-Nearest Neighbors (KNN)
  - Support Vector Regression (SVR)
  - Ensemble methods (e.g., Voting Regressor)
  - XGBoost (an ensemble boosting method)
- **Optimization:** Utilizes [Optuna](https://optuna.org/) for hyperparameter tuning to enhance model performance.
- **Model Interpretation:** Applies SHAP to interpret model predictions and understand feature contributions.
- **Visualization:** Generates plots to compare actual versus predicted RUL values, providing a clear understanding of model performance.

Data was sourced from [Kaggle](https://www.kaggle.com/datasets/ignaciovinuales/battery-remaining-useful-life-rul)
