# bitcoin-price-prediction-using-lstm
Developed a deep learning model using Long Short-Term Memory (LSTM) networks to predict Bitcoin’s closing price based on historical market data. The project aimed to capture the temporal dependencies and volatility of Bitcoin prices to forecast future trends with higher accuracy than traditional machine learning models.
Key Features:
	•	Collected and preprocessed time-series data including daily Open, High, Low, Close, and Volume prices from 2014 to 2024.
	•	Normalized data and created sliding time windows to train the model on sequential historical prices.
	•	Designed and trained a multi-layer LSTM neural network using TensorFlow/Keras to learn temporal patterns.
	•	Split the data into training and testing sets to validate prediction accuracy.
	•	Evaluated the model using Mean Squared Error (MSE) and visualized predicted vs. actual price movements.
	•	Achieved an 85% forecasting accuracy for short-term price trends on the test dataset.

Tools & Technologies:
	•	Python, Pandas, NumPy
	•	TensorFlow / Keras
	•	Matplotlib / Seaborn for data visualization
	•	Scikit-learn for scaling and evaluation

Outcome:
Successfully demonstrated that LSTM networks can model complex temporal relationships in financial time series data and provide valuable insights for cryptocurrency price forecasting.
