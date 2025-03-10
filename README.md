# Bitcoin Price Prediction

## Project Overview
This project aims to predict Bitcoin prices using various time-series forecasting models, including **Prophet**, **Neural Prophet**, and **Long Short-Term Memory (LSTM)** neural networks. By leveraging historical Bitcoin price data, the project explores and compares the effectiveness of these models in forecasting future price movements.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Models Implemented](#models-implemented)
- [Results and Comparisons](#results-and-comparisons)
- [Installation and Usage](#installation-and-usage)
- [Dependencies](#dependencies)
- [License](#license)

## Dataset
The dataset comprises historical Bitcoin price data, including daily opening, closing, high, low prices, and trading volume. This data is essential for training and evaluating the forecasting models.

## Models Implemented
1. **Prophet**: A forecasting tool developed by Facebook, designed for time-series data with daily observations that display seasonality.
2. **Neural Prophet**: An extension of Prophet, incorporating neural network components to capture complex patterns in time-series data.
3. **Long Short-Term Memory (LSTM)**: A type of recurrent neural network (RNN) capable of learning long-term dependencies, suitable for sequential data like time-series.

## Results and Comparisons
The performance of each model is evaluated using metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE). Detailed comparisons and visualizations of the models' predictions versus actual Bitcoin prices are provided in the accompanying [BitcoinPricePrediction_Modelcomparision.pdf](BitcoinPricePrediction_Modelcomparision.pdf) and [BitcoinPricePrediction_Modelcomparision.xlsx](BitcoinPricePrediction_Modelcomparision.xlsx) files.

## Installation and Usage
To replicate the analysis and run the models:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/saivivek55/Bitcoin-Price_Prediction.git
   cd Bitcoin-Price_Prediction

2. **Install the required dependencies: Ensure you have Python installed, then install the necessary packages**:
   ```bash
   pip install -r requirements.txt


3. **Run the Jupyter Notebook:**
   Launch the notebook to explore the data analysis and model implementation**:

   ```bash
   jupyter notebook BitcoinPrice_prediction.ipynb



**License:** This project is licensed under the Apache License 2.0. See the LICENSE.txt file for details.
