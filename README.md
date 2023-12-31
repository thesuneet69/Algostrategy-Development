# Bitcoin Price Prediction with Bidirectional LSTM

In this project, we are planning to leverage a bidirectional LSTM model to predict the future prices of Bitcoin. By collectively analyzing historical price data, preprocessing it, training the model, and generating predictions for the next 24 hours, our goal is to gain valuable insights into potential price movements in the cryptocurrency market.

To accomplish this, we will utilize a variety of libraries such as numpy, pandas, yfinance, sklearn.preprocessing, tensorflow, keras, and matplotlib.pyplot. These libraries will provide us with the necessary tools for efficient data manipulation, preprocessing, model building, training, and visualization.

During the data preprocessing phase, we will download historical Bitcoin price data from the Yahoo Finance API. We will then apply scaling techniques using the MinMaxScaler from the sklearn.preprocessing library to ensure optimal performance during training. Sequences of a specific length will be created using the data, which will be split into training and testing sets.

Next, we will collectively construct a bidirectional LSTM model using the keras API. This model is renowned for its ability to capture long-term dependencies in sequential data. Dropout layers will be incorporated to prevent overfitting, and a dense layer will serve as the final output layer.

To train the model, we will compile it with appropriate loss functions and optimizers. Early stopping and model checkpointing techniques will be employed to prevent overfitting and save the best-performing model.

Once the model is trained, we will evaluate its performance using the testing data. This evaluation will provide us with valuable insights into the model's predictive capabilities and its ability to generalize to unseen data.

Finally, we will utilize the trained model as a team to predict the next 24 hours of Bitcoin prices. By applying inverse transformations to the scaled predictions, we will restore them to their original scale. The resulting predicted prices will be visualized using the matplotlib.pyplot library, enabling us to collectively analyze and interpret future price trends.

Overall, our team project aims to collaboratively leverage a bidirectional LSTM model to forecast Bitcoin prices and provide valuable insights into the dynamic cryptocurrency market.

