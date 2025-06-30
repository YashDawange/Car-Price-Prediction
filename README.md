# 🚗 Car Price Prediction using Machine Learning

This project aims to predict the selling price of used cars using various machine learning models. It includes data preprocessing, feature engineering, model training, and evaluation steps. The goal is to assist buyers and sellers in estimating fair car prices based on relevant attributes.

## 📂 Dataset File: [quikr.csv](./quikr.csv)


## 📁 Project Structure

- `Car Price Prediction.ipynb` — Jupyter Notebook with the complete implementation.
- `README.md` — Project overview and instructions.

## 📊 Dataset

The dataset includes information such as:
- Year of purchase
- Present price
- Kilometers driven
- Fuel type
- Seller type
- Transmission type
- Ownership
- Car name
- Selling price (target)

## 🧠 ML Models Used

- Linear Regression
- Random Forest Regressor

## 🛠️ Key Features

- Data Cleaning & Preprocessing (encoding, feature selection)
- Exploratory Data Analysis (EDA) using Seaborn and Matplotlib
- Model Training and Evaluation using R² Score, Mean Squared Error
- Hyperparameter tuning with `random_state` selection
- Comparison of model performance

## 📈 Results

- Best model: **Random Forest Regressor**
- Achieved an R² score of approximately **0.88**
- Model captures non-linear patterns better than linear regression

## 📦 Libraries Used

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/car-price-prediction.git
   cd car-price-prediction
