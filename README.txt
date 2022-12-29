Currently contains Time Series Prediction of S&P500 Volume for QMiners. In future this repository will be more focused on real Algorithmic Trading bots using Interactive Brokers API.

Algorithmic Trading perfectly merges all my passions: Programming, Machine Learning, Economics and Finance.

Ultimate Goal: Run Transformer ML Model using all indicators listed as an input with ATR Trailing. Using Levariging, Martingale and Volume Strategies. Tested with backtesting python library and using many K-Fold TimeSeries Splits.

## CURRENT STATE
* What I have already implemented and tried out

### INDICATORS
* Technical Indicators

### ML MODELS
* Scikit-learn XGBoost
* Hyperopt parameters tuning

## TODO LIST
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
* Transformer ML (or LTSM in the beginning)
	* Using PyTorch/Tensorflow (prefer PyTorch rn)
	* Training on external GPUs
	* Using Normalization
	* Trying Regularization
	* K-Fold technique
* TimeSeries Algorithms
	* ARIMA
	* SARIMAX
	* Prophet
	* Neural Prophet
* Optuna parameters tuning