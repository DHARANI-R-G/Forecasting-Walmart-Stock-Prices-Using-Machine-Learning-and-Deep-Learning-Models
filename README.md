Stock price prediction remains a complex and persistent challenge in the domain of financial analytics, 
primarily due to the volatile, non-linear, and temporally dependent behavior of financial markets. This study 
presents a comparative evaluation of traditional statistical methods and advanced deep learning architectures 
for forecasting the stock prices of Walmart Inc. (WMT), with a particular focus on each model’s capability to 
capture temporal dependencies inherent in financial time series data. 
Historical adjusted closing prices were obtained from January 2014 to the most recent trading day using the 
Yahoo Finance API. The dataset was normalized using the MinMaxScaler technique, and a 60-day look-back 
window was employed to generate input sequences that encapsulate recent price trends. The models 
implemented in this study include Long Short-Term Memory (LSTM), Gated Recurrent Unit (GRU), 
Bidirectional LSTM (BiLSTM), and Bayesian Ridge Regression. To maintain the chronological integrity of 
the data and ensure realistic forecasting conditions, a time-aware train-test split was utilized. 
Model performance was assessed using a range of evaluation metrics, including Mean Squared Error (MSE), 
Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), the Coefficient of Determination (R²), and 
directional prediction accuracy. Overfitting was systematically monitored by comparing training and testing 
RMSE values, and dropout regularization was incorporated into the deep learning models to enhance 
generalization. 
Among the deep learning models, the GRU demonstrated superior predictive performance, achieving an 
RMSE of 2.036 and an R² of 0.985. However, Bayesian Ridge Regression outperformed all other models in 
both directional accuracy (98.47%) and error minimization (RMSE: 1.017, R²: 0.996), underscoring its 
robustness and interpretability in financial forecasting contexts. 
These results highlight the efficacy of sequence-based deep learning models for capturing temporal patterns 
in stock prices, while also emphasizing the practical trade-offs between model complexity, interpretability, 
and generalization. The findings contribute to the broader understanding of predictive modeling in financial 
markets and inform future model selection for time series forecasting applications.
