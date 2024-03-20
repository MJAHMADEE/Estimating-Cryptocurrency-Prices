# Estimating Cryptocurrency Prices with Machine Learning 📈💰

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

Estimating Cryptocurrency Prices is a machine learning project that leverages deep learning techniques to predict the prices of cryptocurrencies. The project uses LSTM and GRU models to analyze time series data and make predictions about future prices.

## Features 🌟
- Employs LSTM (Long Short-Term Memory) and GRU (Gated Recurrent Units) models for accurate time series forecasting.
- Utilizes a hybrid approach combining features of both LSTM and GRU for enhanced predictions.
- Provides 1-day, 3-day, and 7-day price predictions for cryptocurrencies like Litecoin and Monero.
- Offers detailed visualizations of price trends and model performance metrics.

## Setup and Installation 🛠️
1. Clone the repository from GitHub.
2. Navigate to the project directory.
3. Install the required dependencies listed in the `requirements.txt` file.

## Dataset 📁
The project analyzes historical price data for various cryptocurrencies, focusing on Litecoin and Monero. Data includes daily prices, volume, and other relevant market indicators.

## Model Training and Evaluation 🚀
- The model training process includes loading the pre-processed time series data, normalizing it, and then training using the LSTM and GRU models.
- Model performance is evaluated using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared values.

## Results and Evaluation 📊
- The models' performance can be assessed through the generated prediction plots against actual price movements.
- The evaluation includes a comparative analysis of the LSTM and GRU models across different prediction windows.

## License 📜
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements 🙌
- Data sources include historical price data for various cryptocurrencies.
- TensorFlow and Keras documentation for providing extensive guidance and tutorials.

## Notebook and Copyright
Access the project notebook for a detailed walkthrough of the analysis and modeling process:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1CuLFCg0TqnZf76EFZoQ2U4Ye96GaunzE)

@misc{MJEstimatingCrypto2023,
  author = {Mohammad Javad (MJ) Ahmadi},
  title = {Estimating Cryptocurrency Prices},
  year = {2023},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/MJAHMADEE/Estimating-Cryptocurrency-Prices/}}
}

---
For more information, please refer to the [official repository](https://github.com/MJAHMADEE/Estimating-Cryptocurrency-Prices/).
