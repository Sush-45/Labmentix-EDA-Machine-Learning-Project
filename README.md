#  Yes Bank Stock Price Prediction using Machine Learning

##  Project Overview

This project aims to predict the **closing price of Yes Bank stock** using historical Yes Bank stock price data. The project follows a complete machine learning pipeline, including Exploratory Data Analysis (EDA), data preprocessing, feature engineering, feature selection, model building, hyperparameter tuning, model evaluation, and model explainability.

The objective is to analyze the relationship between different stock price features and build a regression model capable of accurately predicting the closing price.

---

##  Business Objective

The objective of this project is to develop a machine learning model that predicts the closing price of Yes Bank stock. Accurate predictions can help investors and analysts better understand price movements and support data-driven investment decisions.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Joblib
- Jupyter Notebook

---

##  Exploratory Data Analysis (EDA)

During EDA, the dataset was analyzed to:
- Check missing values and duplicates
- Understand data types
- Generate statistical summaries
- Visualize stock price trends
- Analyze feature correlations
- Identify important variables influencing the closing price

---

## Feature Engineering

New features created:
- Price_Range
- Daily_Return
- MA_7 (7-Day Moving Average)
- MA_30 (30-Day Moving Average)

The data was standardized using **StandardScaler** before model training.

---

## Machine Learning Models

The following regression models were implemented:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

Hyperparameter tuning was performed using:
- GridSearchCV
- RandomizedSearchCV

---

## Model Evaluation

The models were evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

After comparing all three models, **Linear Regression** achieved the best performance and was selected as the final prediction model.

---

## Future Scope

- Train the model on larger datasets.
- Include additional financial indicators.
- Develop a real-time stock prediction web application.
- Explore deep learning models such as LSTM for time-series forecasting.

---

##  Author

**Sushmitha Karki**

Computer Science Engineering Student
