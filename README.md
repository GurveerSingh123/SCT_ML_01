# House Price Prediction Using Machine Learning

## Project Overview

This project is a Machine Learning-based House Price Prediction System that predicts house prices using property-related features such as:

- Square Footage
- Number of Bedrooms
- Number of Bathrooms
- Year Built
- Lot Size
- Garage Size
- Neighborhood Quality

The goal of this project is to build a regression model capable of accurately estimating house prices based on housing characteristics.

---

# Dataset Features

| Feature | Description |
|---|---|
| Square_Footage | Size of the house in square feet |
| Num_Bedrooms | Number of bedrooms |
| Num_Bathrooms | Number of bathrooms |
| Year_Built | Construction year of the house |
| Lot_Size | Size of property lot in acres |
| Garage_Size | Garage capacity in number of cars |
| Neighborhood_Quality | Neighborhood rating from 1–10 |
| House_Price | Target variable (house price) |

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
---

# Machine Learning Workflow

## 1. Data Preprocessing

- Checked missing values
- Performed feature analysis
- Applied One Hot Encoding (if categorical data exists)
- Split dataset into training and testing sets

---

## 2. Exploratory Data Analysis (EDA)

Performed:

- Correlation Heatmap
- Scatter Plots
- Histograms
- Boxplots
- Feature Relationship Analysis

---

## 3. Model Training

Trained regression model using Scikit-learn.

Algorithm used:

- Linear Regression

---

# Model Performance

| Metric | Score |
|---|---|
| R² Score | 0.9984 |
| MAE | 8174.58 |
| RMSE | 10071.48 |

---

# Performance Interpretation

- R² score of 0.9984 indicates extremely strong predictive performance.
- MAE shows the average prediction error.
- RMSE indicates overall prediction accuracy while penalizing larger errors.

---


# Future Improvements

- Deploy using Streamlit or Flask
- Hyperparameter tuning
- Cross-validation
- Add interactive dashboard using Power BI

---

# Author

Gurveer Singh

---

