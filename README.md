# ALGORITHMIC TRADING
* Currently contains Time Series Prediction of trading Volume. In future this repository will be more focused on real Algorithmic Trading bots using Interactive Brokers API. Since the task was in predicting the volume, not the stock/forex price, some of the methods could not have been used yet.

## MOTIVATION
* Algorithmic Trading perfectly merges all my passions: Programming, Machine Learning, Economics and Finance.
* Ultimate Goal: Run Transformer ML Model using all indicators listed as an input with ATR Trailing. Using Levariging, Martingale and Volume Strategies. Tested with backtesting python library and using many K-Fold TimeSeries Splits
* It's a great playground for understanding how ML works in practice, not just in theory
	* How to make sure you trust the model enough to put it you real money to trade with
	* How to evaluate that the model is robust
	* Which metrics to use for checking model quality
	* How to seperate data
	* When to normalize them?

## PREREQUSITIES
* pandas-market-calendars
* scikit-learn
* xgboost
* yfinance
* pandas
* pandas_ta
* seaborn
* hyperopt

## CURRENT STATE
* What I have already implemented and tried out

### INDICATORS
* Technical Indicators

### STRATEGIES
* Pandas Market Calendar
* Trading Date Analysis
* Hyperopt parameters tuning

### ML MODELS
* Scikit-learn XGBoost

## WHAT I WANT TO ACHIEVE
* Methods and ideas which kept my eye when I studied the problematic
* I want to try them out using demo account

### INDICATORS
* Custom Indicators
	* Slopes
	* Momentum	
* Custom candlesticks strategies
	* Doji
	* Shooting Stars
	* Hammer
	* Engulfing Patterns

### STRATEGIES
* Pip boundaries
	* ATR Trailing
	* Stop Loss Trailing
* Martingale method
* Backtesting (Cool python Library)
* Levaraging
* K-Fold TimeSeries Split!!
* Volume Trading Strategy

### ML MODELS
* Long short-term memory (LSTM)
	* Using PyTorch/Tensorflow (prefer PyTorch rn)
	* Training on external GPUs
	* Using Normalization
	* Trying Regularization
	* K-Fold technique
	* Switch to Transformers for easier GPU/TPU acceleration
* TimeSeries Algorithms
	* ARIMA
	* SARIMAX
	* Prophet
	* Neural Prophet
* Optuna parameters tuning
