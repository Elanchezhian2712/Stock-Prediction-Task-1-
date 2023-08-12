# Stock-Prediction-Task-1-
This project provides a foundation for understanding and creating stock price prediction models using LSTM. It showcases the complete workflow from data preprocessing to visualization and offers insights into potential avenues for improving accuracy and real-world deployment.



Key Steps:

1. Data Collection: Yahoo Finance API is employed to retrieve historical stock price data for the selected company over a 10-year period.
2. Data Preprocessing: The 'Close' prices are extracted and scaled using MinMaxScaler to fit within a normalized range. The dataset is divided into training and testing sets.
3. Sequences for LSTM: Sequences of data are created, each with a specified sequence length, along with corresponding target values for training the LSTM model.
4. Model Architecture: A Sequential model is constructed with an LSTM layer for capturing sequential patterns, followed by a Dense layer. The model is compiled with an appropriate loss function and optimizer.
5. Model Training: The LSTM model is trained using the training data, with emphasis on optimizing its parameters over 50 epochs.
6. Model Evaluation: The trained model's performance is assessed on both training and testing data, measuring loss to gauge its accuracy.
7. Predictions and Visualization: The model is used to predict stock prices for both training and testing data. These predictions are then transformed back to their original scale and visually compared against actual stock prices.
8. Conclusion and Future Work: The project concludes by summarizing the successful implementation of the LSTM-based stock price prediction model. It highlights potential future enhancements, including fine-tuning model parameters, incorporating additional features, exploring ensemble techniques, enabling real-time prediction, and deploying the model for wider usage.



Outcome:

https://github.com/Elanchezhian2712/Stock-Prediction-Task-1-/assets/122656808/b55311cc-9bac-4951-a83b-b1d1b3ec4a7b

