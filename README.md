# 📈 Daily Stock Price Prediction using LSTM

## 🚀 Overview

This project is an end-to-end **Stock Price Prediction System** that forecasts the **next-day closing price** using historical stock market data. It leverages **LSTM (Long Short-Term Memory)**, a deep learning model designed for time-series forecasting.

The system fetches real-time stock data, processes it, trains a model, and predicts future prices with visualization support.

---

## 🎯 Objective

* Predict next-day stock closing price
* Analyze stock trends using historical data
* Build a real-world time-series forecasting system

---

## 🧰 Tech Stack

* **Programming Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib
* **Machine Learning:** Scikit-learn
* **Deep Learning:** TensorFlow / Keras (LSTM)
* **Data Source:** Yahoo Finance API (yfinance)
* **Deployment (Optional):** Streamlit

---

## 📊 Features

* 📥 Real-time stock data fetching
* ⚙️ Data preprocessing & normalization
* 🔁 Time-series sequence creation (60-day window)
* 🤖 LSTM-based deep learning model
* 📈 Visualization of stock trends
* 🔮 Next-day price prediction
* 🌐 Optional interactive UI using Streamlit

---

## 📁 Project Structure

```
stock-price-prediction/
│
├── data/                # Dataset storage
├── models/              # Saved trained models
├── app.py               # Streamlit app
├── train.py             # Model training script
├── predict.py           # Prediction script
├── utils.py             # Data fetching utilities
├── requirements.txt     # Dependencies
└── README.md            # Project documentation
```

---

## ⚙️ Installation

```bash
git clone https://github.com/yourusername/stock-price-prediction.git
cd stock-price-prediction
pip install -r requirements.txt
```

---

## ▶️ Usage

### 1️⃣ Train the Model

```bash
python train.py
```

### 2️⃣ Run Prediction

```bash
python predict.py
```

### 3️⃣ Launch Web App (Optional)

```bash
streamlit run app.py
```

---

## 📊 Model Details

* Model: **LSTM (Long Short-Term Memory)**
* Input: Last 60 days of stock prices
* Output: Next day predicted closing price
* Loss Function: Mean Squared Error (MSE)
* Optimizer: Adam

---

## 📈 Sample Output

* Graph of historical stock prices
* Comparison of actual vs predicted prices
* Next-day predicted value

---

## 🧠 Key Concepts Used

* Time Series Forecasting
* Deep Learning (LSTM)
* Data Normalization (MinMaxScaler)
* Sliding Window Technique

---

## 🚧 Limitations

* Does not include external factors (news, sentiment, global events)
* Predictions may vary due to market volatility

---

## 🔥 Future Enhancements

* 📊 Add technical indicators (RSI, MACD)
* 📰 Integrate news sentiment analysis (NLP)
* 💡 Buy/Sell recommendation system
* ☁️ Deploy on AWS / Render / Hugging Face
* 📉 Improve accuracy using GRU / Transformers

---

## 👨‍💻 Author

**Hari Narayana Rao Chepuri**

* 📧 Email: [your-email@example.com](mailto:your-email@example.com)
* 🔗 LinkedIn: https://linkedin.com/in/yourprofile
* 💻 GitHub: https://github.com/yourusername

---

## ⭐ Contributing

Contributions are welcome! Feel free to fork this repo and submit a pull request.

---

## 📜 License

This project is licensed under the MIT License.

---

## 💡 Acknowledgements

* Yahoo Finance for stock data
* TensorFlow & Keras for deep learning framework

---

## 🚀 Final Note

This project demonstrates the implementation of **real-world machine learning and deep learning techniques** for financial forecasting and showcases strong skills in **data science, modeling, and deployment**.
