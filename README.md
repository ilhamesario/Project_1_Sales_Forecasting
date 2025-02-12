# Project_1_Sales_Forecasting

## Overview
*Tujuan proyek ini yaitu memprediksi penjualan berdasarkan data historis menggunakan metode VARMAX dan LSTM

## Dataset
*Data source : store5.csv
*Description of key features (date, sales, promotion, external variables) :
-id
-Date 
-Store_nbr: store_nbr
-Family: Class Produk
-Sales: Total Penjualan
-Onpromotion: Total promo yang diberikan oleh toko
-Dcoilwtico: Index harga minyak yang bisa mempengaruhi penjualan barang
*Handling missing value and date.

## Tools & Technologies Used
*Environment: Google Colab.
*Modeling Tools:
-VARMAX using statsmodels.tsa.statespace.varmax.VARMAX
-LSTM using tensorflow.keras

## Data Preprocessing
*Feature normalization / standardization.
*Time transformations (lag features, differencing for VARMAX).
*Splitting data into train and test sets.

## Model Development
*VARMAX : Selecting optimal parameters (p, q), performance evaluation using MSE or AIC/BIC.
*LSTM : Model architecture (number of layers, dropout, activation functions), hyperparameter selection (optimizer, batch size, epochs), callback functions such as EarlyStopping

## Model Evaluation & Comparison
Evaluation metrics: RMSE, MAE, MAPE.
Performance comparison of VARMAX vs. LSTM.
Visualization of predictions vs. actual values.
