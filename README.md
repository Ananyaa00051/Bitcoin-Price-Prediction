

# Bitcoin Price Prediction using Machine Learning

This project explores how to use machine learning models to predict Bitcoin prices based on historical data. The notebook walks through data preprocessing, feature engineering, model training, and evaluation.

## 📁 Project Contents

* `Bitcoin-Price-Prediction-using-Machine-Learning-in-Python.ipynb`: Jupyter notebook containing the full implementation from data analysis to model prediction.
* `bitcoin.csv`: Dataset containing historical Bitcoin price and market data.

## 📊 Dataset

The dataset used includes Bitcoin prices from 2012 to 2020. It contains features like:

* Open, High, Low, Close prices
* Volume and Market Cap

(Data source: [Kaggle Bitcoin Historical Data](https://www.kaggle.com/sudalairajkumar/cryptocurrencypricehistory) or similar)

## 🛠️ Libraries Used

* `pandas`
* `numpy`
* `matplotlib`
* `seaborn`
* `scikit-learn`
* `xgboost`

## 📌 ML Models Used

* Linear Regression
* Decision Tree Regressor
* XGBoost Regressor

Each model is evaluated using metrics such as:

* R² Score
* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/Ananyaa00051/Bitcoin-Price-Prediction.git
   cd Bitcoin-Price-Prediction
   ```

2. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:

   ```bash
   jupyter notebook Bitcoin-Price-Prediction-using-Machine-Learning-in-Python.ipynb
   ```

## 📈 Result

The project compares the performance of different regression models on predicting Bitcoin prices. XGBoost typically performs better due to its ability to handle non-linearity and overfitting.

## ⚠️ Disclaimer

This project is for educational purposes only. The source code and dataset were adapted from public resources. It is **not intended for financial advice or trading**.

## 📄 License

This project is licensed under the **MIT License**.

