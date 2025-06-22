
# Bitcoin Price Prediction

A project to predict Bitcoin prices using historical data and machine learning models.

## Overview
This project analyzes historical Bitcoin price data to forecast future trends. It includes data preprocessing, visualizations, and a predictive model developed by me.

## Setup
1. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
2. Run the script:
   ```bash
   python predict.py
   ```
   Or open `notebook.ipynb` in Jupyter Notebook.

## Dataset
- **Source**: Historical Bitcoin price data included as `bitcoin.csv`.
- **Note**: Ensure the dataset is in the project folder. For a larger dataset, use [Kaggle Bitcoin Historical Data](https://www.kaggle.com/datasets/mczielinski/bitcoin-historical-data).

## Files
- `predict.py`: Python script for data analysis and price prediction.
- `notebook.ipynb`: Jupyter notebook with data exploration and visualizations.
- `bitcoin.csv`: Historical Bitcoin price data.

## Features
- Data cleaning and preprocessing.
- Visualizations of price trends.
- Machine learning model for price prediction (e.g., Linear Regression or LSTM).

## Results
- Predicted Bitcoin prices for the next 7 days.
- Visualizations comparing predicted vs. actual prices.
