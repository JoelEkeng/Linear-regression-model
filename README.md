# Linear Regression Model for Housing Statistics

## Overview
This project applies a **Linear Regression** model to analyze and predict housing prices based on publicly available housing statistics data. The dataset includes various features such as property size, number of bedrooms, location, rental price, occupancy rate, and socioeconomic factors affecting housing affordability.

## Dataset
The dataset consists of:
- **Property Features**: Number of bedrooms, property size (sq ft), number of bathrooms, etc.
- **Location Information**: City, neighborhood, ZIP code.
- **Market Factors**: Rental price, occupancy rate, property age.
- **Economic Indicators**: Average income in the area, crime rate, school ratings.

## Objectives
- Perform **exploratory data analysis (EDA)** to identify trends and relationships.
- Preprocess data (handle missing values, encode categorical variables, normalize numerical features).
- Train a **Linear Regression model** to predict housing prices.
- Evaluate the model using metrics such as **Mean Squared Error (MSE)** and **R² Score**.

## Installation & Dependencies
To run this project, install the required dependencies using:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Model Evaluation
The model is evaluated using:
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **R² Score**

## Results
- Feature importance analysis shows that **property size and location** are the strongest predictors of price.
- The model achieves an **R² score of ~0.85**, indicating good predictive power.

## Future Improvements
- Use **Polynomial Regression** to capture non-linearity.
- Apply **Gradient Boosting (XGBoost, LightGBM)** for better performance.
- Experiment with **additional socioeconomic factors** to improve accuracy.
