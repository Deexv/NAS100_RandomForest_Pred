# NASDAQ 100 Price Prediction with Random Forest Classifier
This repository contains Python code for predicting stock price movements using the Random Forest Classifier algorithm. The code utilizes the Yahoo Finance API to retrieve historical stock data and then trains a Random Forest model to predict whether the stock price will increase or decrease in the future.

## Setup
### To run the code, make sure you have Python installed on your system. You can install the required libraries using pip:

bash
Copy code
```
pip install yfinance scikit-learn pandas
```
## Usage
### Clone the repository:
bash
Copy code
```
git clone https://github.com/Deexv/NAS100_RandomForest_Pred.git
cd NAS100_RandomForest_Pred
```
### Run the Python script:
bash
Copy code
```
python stock_prediction.py
```
## Code Overview
### The main components of the code include:

Data Retrieval: Historical stock data is fetched using the Yahoo Finance API (yfinance library).
Data Preprocessing: The data is cleaned and processed to remove unnecessary columns and handle missing values.
Model Training: A Random Forest Classifier model is trained on the historical stock data.
Prediction: The trained model is used to predict future stock price movements.
Evaluation: The precision score of the model is calculated to evaluate its performance.
Results
The code provides predictions for stock price movements based on the trained Random Forest model. The precision score indicates the accuracy of the predictions.

## Note
This code is provided for educational purposes and should not be used for making actual financial decisions without proper consultation and analysis.
## Contributors
- Deexv
### Feel free to contribute to this project by opening issues or pull requests. Happy predicting!
