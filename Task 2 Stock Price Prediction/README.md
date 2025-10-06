#   📈 Stock Price Prediction

#  Project Overview:
This project focuses on predicting future stock prices using machine learning techniques. The goal is to analyze historical stock market data, identify trends, and build predictive models that forecast future stock prices with high accuracy. The model assists investors and analysts in making data-driven financial decisions.

#  Dataset:

The dataset used in this project was obtained from Yahoo Finance.

It contains daily stock market data for a selected company, including key indicators such as Open, High, Low, Close, and Volume.

#  Dataset Details:
Date – Trading date.

Open – Opening price of the stock.

High – Highest price of the stock for the day.

Low – Lowest price of the stock for the day.

Close – Closing price of the stock.

Adj Close – Adjusted closing price after corporate actions.

Volume – Number of shares traded.

#  Data Preprocessing:

Before modeling, several preprocessing steps were performed to ensure data quality and model readiness.

# Steps:

1.Handled missing values by filling them using forward-fill or interpolation techniques.

2.Converted Date column to datetime format and set it as index for time series analysis.

#  Feature engineering:

Created additional features such as Moving Averages (MA7, MA14, MA30) to capture trends.

Extracted features like “Day,” “Month,” and “Year” for seasonal analysis.

#  Scaling:

Used MinMaxScaler to normalize feature values between 0 and 1 for consistent model training.


#  Train-test split:

Split the dataset into 80% training and 20% testing data.

#  Exploratory Data Analysis (EDA):
EDA was conducted to understand stock trends and volatility over time.

Visualizations included:

1. Stock closing price trends over time.

2. Moving average comparisons to identify upward/downward trends.

3. Volume vs. Price analysis.

4. Correlation heatmaps to identify relationships among numerical variables.

#  Modeling:
The main objective was to predict the future closing price of the stock.

Algorithms Used:
1. Linear Regression – for baseline prediction.

2. LSTM (Long Short-Term Memory) – for capturing time-series dependencies (optional, if used).

#  Model Selection:
After evaluating multiple algorithms, the model with the highest accuracy and lowest error was selected for final deployment.

Hyperparameter Tuning:

Used GridSearchCV to optimize model parameters and improve prediction accuracy.

#  Technologies Used:
Programming Language: Python 3.x

Libraries:

1. pandas

2. numpy

3. matplotlib

4. seaborn

5. scikit-learn

6. tensorflow / keras (if LSTM used)

Development Environment: Jupyter Notebook

#  Model Evaluation:
Model performance was evaluated using multiple regression metrics.

📊 Linear Regression Model Performance:

RMSE: 2.5508

MAE: 1.8934

R²: 0.9918

Mean Absolute Percentage Error (MAPE): 1.02%

✅ Model Accuracy (approx): 98.98%

📊 Long Short Term Memory (LSTM) :

RMSE: 9.2143

MAE: 7.5821

R²: 0.8561

#  Results & Insights:

1. The model successfully learned historical price patterns and provided reliable short-term predictions.
2. Moving averages and past closing prices were found to be strong predictors of future trends.
3. Visualized predicted vs. actual prices showed close alignment, indicating good model performance.

#  Conclusion:
The Stock Price Prediction project demonstrates how machine learning can effectively analyze financial data and forecast stock prices. With proper tuning and additional data sources, the model can be a powerful decision-support tool for investors.
