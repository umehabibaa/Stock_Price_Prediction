# Stock Price Prediction (Short-Term) 
This project uses historical stock data to predict the next day's closing price using Machine Learning techniques.

## Objective
- Predict next-day closing price for a selected stock using features like Open, High, Low, and Volume.
- Compare predicted prices against actual closing prices using visualizations.

## Dataset
Stock market data fetched from Yahoo Finance using the yfinance Python library.

## Technologies & Libraries
- Python
- yfinance
- pandas
- scikit-learn
- matplotlib

## Project Workflow
1. Data Collection
Stock data retrieved via yfinance.

2. Data Exploration
- Basic info and structure of the dataset examined.
- Missing values checked and handled.

3. Model Building
- Random Forest Regressor model trained to predict the next day's closing price.
- Dataset split into training and testing sets for evaluation.

4. Evaluation
Predicted vs. actual closing prices plotted for visual comparison.

## Results
The notebook produces line plots showing predicted closing prices alongside actual closing prices. Visual comparison provides insights into model performance.

## Disclaimer
This project is for educational purposes only and not intended for real-world financial decision-making or trading.

## Acknowledgments
- Yahoo Finance for providing free stock market data.
- Scikit-learn for machine learning models.
