# Deep Learning for Stock Time Series Forecasting

This project explores time series prediction using deep learning models applied to real-world stock market data. 
The dataset includes historical features: Date, Open, High, Low, Close, Volume.

## Models & Methods
1D Convolutional Neural Network (CNN):
Learns short-term temporal patterns using convolutional feature extraction.

Long Short-Term Memory (LSTM):
Captures long-term sequential dependencies in financial time series data.

## ML / AI Concepts Demonstrated
- Time series windowing and sequence modeling
- Feature normalization and data preprocessing
- Deep neural network architecture design
- Model evaluation using Mean Squared Error (MSE)
- Training vs validation loss analysis for overfitting detection

## Tech Stack
- Programming Language: Python
- Deep Learning: TensorFlow / Keras
- Data Processing: NumPy, Pandas
- Visualization: Matplotlib
- Model Evaluation: Mean Squared Error (MSE)

## Key Insights
- CNN achieved strong generalization with stable validation performance.
- LSTM showed lower training error but signs of overfitting, emphasizing the importance of regularization and architecture tuning in sequence models.
- This project demonstrates hands-on experience with deep learning for time series forecasting, model comparison, and practical ML evaluation techniques.
