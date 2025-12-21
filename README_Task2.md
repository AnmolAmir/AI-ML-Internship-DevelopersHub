# Task 2: Predict Future Stock Prices (Short-Term)

## Objective
Predict the next day's closing price of a stock using historical stock data from Yahoo Finance.

## Dataset
- Stock market data fetched via `yfinance`  
- Features used: Open, High, Low, Volume  
- Target variable: Close price

## Model
- Linear Regression (from scikit-learn)

## Key Steps
1. Load stock data using `yfinance`
2. Select features (Open, High, Low, Volume) and target (Close)
3. Split data into train and test sets (80/20)
4. Train Linear Regression model
5. Predict closing prices on test set
6. Visualize actual vs predicted closing prices

## Results
- Visual plot shows predicted prices vs actual prices  
- Model captures general trends but exact prediction is limited due to market volatility

## Notes
- Model accuracy can be improved using more advanced methods like Random Forest or LSTM for time series
