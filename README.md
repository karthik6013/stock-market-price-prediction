# stock-market-price-prediction
# Stock Price Prediction

## Overview
This project aims to predict stock prices using machine learning techniques. The model is trained on historical stock data and optimized using Hyperopt and Talos for hyperparameter tuning.

## Features
- Data preprocessing and visualization
- Stock price prediction using machine learning
- Hyperparameter tuning with Hyperopt and Talos
- Outputs graphs for prediction vs real stock prices

## Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- TensorFlow/Keras
- Hyperopt, Talos
- Matplotlib for visualization

## Installation
1. Clone the repository:
   ```bash
   git clone <repo-url>
   cd Stock-Price-Prediction-master
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
Run the main prediction script:
```bash
python stock_pred_main.py
```
To optimize hyperparameters using Hyperopt:
```bash
python stock_pred_hyperopt.py
```
To optimize using Talos:
```bash
python stock_pred_talos.py
```

## Outputs
Predicted vs Real stock prices and training vs validation loss graphs are saved in the `outputs/` folder.

## Contributing
Feel free to fork this repository and submit pull requests.
