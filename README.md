# 📈 Stock Price Prediction using Python & Machine Learning

A comprehensive stock price prediction project built entirely in **Python**, leveraging powerful data science libraries such as **yfinance**, **Pandas**, **Scikit-learn**, and **Matplotlib**. The project demonstrates a full end-to-end workflow for fetching financial data, preprocessing, training a machine learning model, and evaluating performance with **backtesting techniques**.

---

## 🧠 Project Objective

To predict future stock price movements using historical stock data, applying machine learning — specifically the **Random Forest Classifier** — and evaluate model accuracy using precision scores and backtesting methods.

---

## 📦 Tech Stack

- **Python 3**
- `yfinance` – for historical stock price data
- `pandas` – for data manipulation and cleaning
- `scikit-learn` – for model building (Random Forest)
- `matplotlib` – for data visualization
- `numpy` – numerical operations

---

## 🔍 Data Collection

- Used the `yfinance` library to fetch historical stock data.
- Dataset ranges from **1950 to 2025**.
- To enhance model relevance and accuracy, the dataset was **filtered to include only data from January 1, 1990 onward**.

---

## 🧹 Data Preprocessing

- Final 100 rows of the dataset were set aside for testing.
- All remaining data was used for training the model.
- Feature engineering and data cleaning were applied using `pandas`.
- Boolean columns were created to evaluate whether predictions matched actual outcomes.

---

## 🧪 Model Building

- Implemented a **Random Forest Classifier** using `scikit-learn`.
- Initial training was performed on the historical dataset (excluding the final 100 rows).
- Predictions were validated using the test set and compared against actual values.
- Performance was measured using the **Precision Score** metric.

---

## 🔁 Backtesting and Improvement

- Based on initial evaluation, a **backtesting strategy** was implemented to better simulate real-world predictions.
- The model was retrained with refined data and techniques.
- Accuracy was reassessed, and the **precision score was improved to just above 57%**.

---

## 📊 Results & Key Findings

- Model successfully captured short-term price movement patterns.
- After backtesting and retraining, achieved **57%+ precision score**, indicating moderate but meaningful predictive power.
- Further improvements could involve additional features (technical indicators, volume trends, etc.) and advanced models like LSTM or XGBoost.

---

## 🚀 Future Work

- Incorporate more features like RSI, MACD, moving averages.
- Explore deep learning models for time series (LSTM, GRU).
- Use ensemble methods for combining predictions.
- Build an interactive dashboard using Plotly/Dash or Streamlit.

---

## 📁 Project Structure

```bash
📦stock-price-prediction/
 ┣ 📄 main.py
 ┣ 📄 model_training.py
 ┣ 📄 data_fetching.py
 ┣ 📄 README.md
 ┗ 📄 requirements.txt
```

---

## 🛠️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/stock-price-prediction.git
cd stock-price-prediction
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the script:

```bash
python main.py
```

---

## 📌 Dependencies

```
yfinance
pandas
scikit-learn
matplotlib
numpy
```

---

## 🙌 Acknowledgments

- Yahoo Finance for historical data access.
- Scikit-learn documentation for easy-to-use ML tools.

---
