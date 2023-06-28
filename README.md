# Stock Price Prediction using Linear Regression

This project demonstrates how to use the Alpha Vantage API to retrieve historical stock prices, train a linear regression model, make predictions, and evaluate the accuracy of the model.

## Description

The project consists of the following steps:

1. Retrieve historical stock prices using the Alpha Vantage API.
2. Process the API response and extract the closing prices.
3. Split the data into training and testing sets.
4. Train a linear regression model using the training data.
5. Make predictions on both the training and testing data.
6. Evaluate the accuracy of the model using the coefficient of determination (R-squared).
7. Plot the actual and predicted stock prices on a graph.

## Dependencies

The following dependencies are required to run the code:

- requests
- pandas
- scikit-learn
- matplotlib

## Usage

1. Sign up for an API key at the Alpha Vantage website: https://www.alphavantage.co/.
2. Run the code to retrieve the stock prices, train the model, and generate predictions.
3. The actual and predicted stock prices will be printed, along with the accuracy score.
4. A graph showing the actual and predicted prices will be displayed.

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to customize and modify the code to suit your needs.

## Credits

- Alpha Vantage API: https://www.alphavantage.co/
- scikit-learn: https://scikit-learn.org/
- matplotlib: https://matplotlib.org/

