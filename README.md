# Project Title: Home Price Prediction

**File:** `Home_Price_Prediction.ipynb`

#### Description:
This notebook addresses a regression problem to predict home prices based on various features. The workflow includes:
- Data preprocessing (handling missing values, encoding categorical data)
- Exploratory Data Analysis (EDA) for insights into the dataset
- Building and evaluating multiple regression models
- Model comparison to determine the best-performing model

#### Dataset:
- **Source:** The dataset is loaded using the `fetch_california_housing()` function from `sklearn.datasets`.
- **Description:** This dataset includes data on various aspects of housing in California, such as median income, average house age, and number of rooms. The target variable is the median house value for California districts.
- **Usage:** A standard dataset for exploring regression techniques and feature engineering.

#### Key Highlights:
- Covers linear regression, ridge regression, and Lasso regression.
- Includes hyperparameter tuning for model optimization.
- Provides detailed analysis of feature importance and prediction accuracy.

#### Dependencies:
- Python 3.x
- Libraries: `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`
