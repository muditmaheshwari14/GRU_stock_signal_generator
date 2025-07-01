# GRU_stock_signal_generator
A simple time series model to generate buy and sell signals on stocks, the model can be trained and tested on any stock or asset class. It is a single stock signal generator which uses GRU model to train on stock data and the features engineered to predict next 10 day stock prices.
Its signal generation works based on the max upside and downside it predicts, To test its performance a backtester code is compiled to test its performance on unseen market prices and can be analyzed using the the equity curve it plots  and also a detailed analysis can be done on the trade logs it generates.
Future work can be done using Reinforcement learning models to tran and adapt using the signals generated for better performance.

Result:-

![image](https://github.com/user-attachments/assets/fc9fb935-6cd2-49df-9172-a8d18afa5352)
