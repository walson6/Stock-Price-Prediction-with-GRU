###   Project Title: Stock Price Prediction with GRU Models

**Objective:** 
To predict stock prices for companies in the CAC40 index using time series forecasting with Gated Recurrent Unit (GRU) models.

**Implementation:**
1. **Data Preparation:**
   - Collected historical stock price data for CAC40 companies (including open, close, high, low, and volume).
   - Preprocessed the data by cleaning and normalizing the stock prices to ensure consistency and facilitate model training.
   - Split the data into training and test sets, with 80% for training and 20% for testing.
   - Scaled the stock price features using MinMaxScaler to bring them into a range of [0, 1].
2. **Model Training and Evaluation:**
   - GRU Model:
       - Architecture: A GRU layer followed by a dense layer to predict the future stock price.
       - Trained for 50 epochs with a batch size of 64.
       - Achieved a Root Mean Squared Error (RMSE) of 3.45.
       - Observations: The GRU model provided a slightly less accurate prediction than LSTM but was computationally more efficient.

3. **Model Evaluation:**
   - Evaluated each model using RMSE and Mean Absolute Percentage Error (MAPE) to assess prediction accuracy.
   - Visualized the predicted stock prices versus actual prices using Matplotlib, showing how well the models tracked market trends.

**Skills Demonstrated:**
   - Proficiency in Python and TensorFlow/Keras for time series forecasting.
   - Knowledge of GRU architectures and their application in stock price prediction.
   - Experience with data preprocessing techniques such as normalization and splitting.
   - Evaluation of model performance using metrics like RMSE and MAPE.
   - Visualization skills for presenting model results and comparing predicted vs. actual outcomes.

**Tools and Libraries Used:**
   - Python
   - TensorFlow
   - Keras
   - pandas
   - NumPy
   - Matplotlib
