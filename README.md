# 📈 GameStop Stock Price Prediction with Facebook Prophet

This project uses 5 years of historical stock data for GameStop (GME) to forecast the stock price for the next 30 days using Facebook's open-source time series forecasting tool, **Prophet**.

## 🔍 Overview

- ⏳ Timeframe: Last 5 years of stock data
- 🧠 Model: Facebook Prophet
- 🎯 Goal: Predict GameStop's stock price movement for the next 30 days
- 📊 Visualization: Forecast plot, trend components

## 📦 Requirements

Make sure the following libraries are installed:

```bash
pip install yfinance prophet matplotlib pandas
````

🚀 How to Run

1. Clone this repository:

````
git clone https://github.com/Z0G/GameStop-Price-Forecast-Using-Facebook-Prophet-Model

cd GameStop-Price-Forecast-Using-Facebook-Prophet-Model
````

2. Run the notebook:

    - Open GameStopPriceForecast.ipynb using Jupyter or any compatible notebook editor.

    - Execute all cells in order.

3. The notebook:

    - Prepares the data for forecasting

    - Trains a Prophet model

    - Predicts stock price for the next 30 days

    - Plots the results
  
    - Downloads the forecasted data

📊 Example Output

Forecast sample plot:

![image](https://github.com/user-attachments/assets/1f8ee1f9-8501-4d07-aea8-c3dfb04f62c5)

🛠️ Project Structure
````
📁 GameStop-Price-Forecast-Using-Facebook-Prophet-Model
├── GameStop.csv
├── GameStopPriceForecast.ipynb
├── README.md
├── LICENSE
````
🧑‍💻 Author

Mohammad Shoumik Raihan (https://github.com/Z0G)

📜 License

This project is licensed under the MIT License - see the LICENSE file for details.
