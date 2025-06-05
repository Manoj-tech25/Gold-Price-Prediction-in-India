# Gold-Price-Prediction-in-India
Gold Price Prediction in India (based on US price) by Using python 
# 📈 Gold Price Prediction in India (Based on USD Price)

This project predicts the **gold price in India** using gold prices in **USD**, fetched from Yahoo Finance using the `yfinance` library. It includes data cleaning, merging, EDA, machine learning, and an interactive Gradio app.

---

## ✅ Features

- Downloaded **gold price in USD** using `yfinance`
- Merged with **1-year gold price in INR**
- Cleaned and arranged data by date and price
- Performed **EDA (Exploratory Data Analysis)**
- Used **Regex** for advanced cleaning (if needed)
- Applied **train-test split** and **StandardScaler**
- Built a **regression model** to predict INR gold prices
- Created a **Gradio app** for user-friendly prediction

---

## 🛠️ Technologies Used

- `yfinance`
- `pandas`
- `numpy`
- `matplotlib` / `seaborn`
- `scikit-learn`
- `gradio`

---

## 📂 Datasets

- **Gold Price (USD)** – downloaded using `yfinance`
- **Gold Price (INR)** – custom dataset (1-year data)

---

## 🚀 How to Run the Project

1. **Install Dependencies**:
   ```bash
   pip install yfinance pandas numpy matplotlib seaborn scikit-learn gradio
---

##🧠 ML Model Info
**Model**: (e.g., Linear Regression, Random Forest)

**Features scaled using StandardScaler**

**Input**: USD gold price

**Output**: Predicted INR gold price

├── app.py               # Main app with Gradio interface
├── indian_gold.csv      # INR gold prices (your dataset)
├── usd_gold.csv         # USD gold prices from yfinance
├── README.md            # Project documentation

---

##🙏 Credits
Data Source: Yahoo Finance

Tools: Gradio, Scikit-learn, Pandas, Matplotlib

