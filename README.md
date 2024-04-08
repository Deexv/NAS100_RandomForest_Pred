# Stock Price Prediction using Random Forest Classifier

## Overview
This Python script aims to predict the future direction of the NASDAQ-100 index (NQ=F) using historical price data and a Random Forest Classifier model. The script fetches historical data using the Yahoo Finance API (`yfinance`), preprocesses the data, trains the model, and evaluates its performance.

## Code Outline
The script can be divided into the following main sections:

1. **Data Retrieval**: Fetch historical price data for the NASDAQ-100 index using the `yfinance` library.
2. **Data Preprocessing**: Prepare the data for modeling by cleaning and transforming it.
3. **Feature Engineering**: Create additional features from the raw data to improve model performance.
4. **Model Training**: Train a Random Forest Classifier model using the preprocessed data.
5. **Model Evaluation**: Evaluate the model's performance using precision score and visualize the predictions.
6. **Backtesting**: Conduct backtesting to assess the model's effectiveness over different time horizons.

## Detailed Description

### 1. Data Retrieval
- Utilizes the `yfinance` library to fetch historical price data for the NASDAQ-100 index.
- Retrieves data for the desired period with a daily interval.

### 2. Data Preprocessing
- Cleans the raw data by removing unnecessary columns and handling missing values.
- Prepares the data for feature engineering and model training.

### 3. Feature Engineering
- Creates additional features such as moving averages, trend indicators, and ratios to improve model performance.
- Enhances the dataset by adding informative variables derived from the original data.

### 4. Model Training
- Trains a Random Forest Classifier model using the preprocessed data.
- Utilizes a subset of features as predictors and the target variable to train the model.

### 5. Model Evaluation
- Evaluates the performance of the trained model using precision score, a metric for classification models.
- Visualizes the model's predictions compared to the actual target values.

### 6. Backtesting
- Conducts backtesting to assess the model's effectiveness over different time horizons.
- Evaluates the model's predictive power over various rolling windows to analyze its robustness.

## Requirements
- Python 3.x
- `yfinance` library
- `pandas`
- `scikit-learn` library for the Random Forest Classifier

## Usage
1. Ensure all required libraries are installed using `pip install -r requirements.txt`.
2. Run the script in a Python environment such as Jupyter Notebook or any Python IDE.

## Disclaimer
- This script is provided for educational and informational purposes only.
- Stock market prediction involves inherent risks, and past performance is not indicative of future results.
- Use this script at your own risk. The author and OpenAI do not guarantee any specific outcome or profitability.

## Contributing
- Contributions and improvements to the script are welcome. Fork the repository, make your changes, and submit a pull request.

## License
- This script is licensed under the MIT License. See the LICENSE file for details.

## Support
- For questions or issues, please open an issue in the repository or contact the author directly.

## Acknowledgments
- Special thanks to the developers of `yfinance` and the Python community for their contributions and support.
  
Feel free to modify and extend the script according to your needs, and happy trading!
