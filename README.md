# Asset-Forecasting_Portfolio-Optimization

Repo contains pieces for a 
  - Deep Reinforcement Learning model (DRL) for Portfolio Optimization (off-policy model-free deep deterministic policy gradient model)
  - Long Short Term Memory model for Asset Price Forecasting

    
The DRL model rarely will converge. The Dataset_Builder was made to be able to generate new datasets easily. Inorder to use said function you must obtain a Binance.us api-key/secret and change corresponding variables at the beginning of the block.
This is also true for the custom LSTM model called 'own_data_lstm'. The 'standard_lstm' is available for use because it pulls data from yahoo finance. 

