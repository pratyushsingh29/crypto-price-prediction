# Crypto Price Prediction using Linear Regression

## About the Project

This is one of my first machine learning projects where I built a Linear Regression model to predict the closing price of cryptocurrencies.

The objective of this project was not only to build a prediction model but also to understand the complete machine learning workflow, from loading data to evaluating model performance.

## What I Learned

While working on this project, I learned how to:

- Load and explore datasets using Pandas
- Select features and target variables
- Split data into training and testing sets
- Standardize numerical features using StandardScaler
- Train a Linear Regression model
- Evaluate the model using MAE, RMSE, and R² Score
- Visualize predictions using Matplotlib

## Dataset

The dataset contains daily cryptocurrency market data, including:

- Open Price
- High Price
- Volume
- Close Price

For this project, I used:

**Features**
- Open Price
- High Price
- Volume

**Target**
- Close Price

## Results

The model achieved:

- MAE: **78.91**
- RMSE: **243.89**
- R² Score: **0.9997**

The high R² score is mainly because the model predicts the closing price using other prices from the same trading day (Open and High), which are naturally highly correlated.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Future Improvements

This project is my first step into machine learning. In future versions, I plan to:

- Experiment with Decision Trees and Random Forests
- Build a proper time-series forecasting model
- Predict future prices instead of same-day closing prices
- Deploy the model using Streamlit

## Author

**Pratyush Singh Burman**

First-year Integrated MBA (Data Science & AI)

IIT Mandi
