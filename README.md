# CS 715 - Project : Predicting Stock Prices Using a Three-Layer LSTM Model on Alphabet Inc (GOOG)

### Introduction
Hansun and Young demonstrated the efficacy of a three-layer LSTM model in predicting the closing prices of stocks in the LQ45 financial index. Their approach involved preprocessing financial time series data, applying normalization, and utilizing an LSTM model comprising an LSTM layer, a dropout layer to prevent overfitting, and a dense layer as the output. The study yielded promising results, with performance evaluated using Mean Absolute Percentage Error (MAPE) and Root Mean Square Error (RMSE). This project proposes to extend their methodology to a new domain: the stock price prediction of Alphabet Inc (GOOG). Unlike the LQ45 index stocks, Alphabet Inc represents a technology-focused, highly traded security on the NASDAQ stock exchange, offering an opportunity to explore the model's adaptability and robustness in predicting prices in a different market segment.

### Objective
This project aims to apply and evaluate the three-layer Long Short-Term Memory (LSTM) neural network model proposed by Hansun and Young (2021) to predict the Open, Close, High, and Low prices of Alphabet Inc (GOOG). By leveraging the principles and methodology described in their study, this project will adapt the model to a different dataset and assess its effectiveness.


This project will follow the steps that were described in the said research to verify their findings and result.

### Steps

Setup and Import Libraries
Data Collection and Preprocessing
Model Architecture
Evaluate the Model
Visualization of Results

Visit Python Notebook attahced for detailed implementation.

### Results


<img width="1384" height="1190" alt="stock_price_Prediction_Single Step" src="https://github.com/user-attachments/assets/4f4c9f08-7319-48c8-ac76-2fd06e743717" />

<img width="1340" height="1000" alt="multi_step_Prediction" src="https://github.com/user-attachments/assets/7500d385-024d-4631-bec2-cbb45cbc5eb9" />


