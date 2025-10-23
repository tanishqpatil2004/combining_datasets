# 🧠 Market Sentiment vs Trader Performance Analysis

This project explores the intricate relationship between **market sentiment** and **trader performance** using real-world cryptocurrency trading and sentiment data. By combining **Bitcoin Market Sentiment** metrics with **Historical Trader Data**, this notebook uncovers patterns that can inform smarter, data-driven trading strategies.

---

## 📊 Project Overview

The primary goal of this project is to understand **how emotional market states (Fear/Greed)** influence **trader behavior and profitability**.  
Through systematic data merging, feature engineering, and model evaluation, the notebook identifies which predictive modeling approach best captures this relationship.

---

## 🧩 Datasets Used

1. **Bitcoin Market Sentiment Dataset**
   - **Columns:** `Date`, `Classification` (Fear/Greed)
   - Reflects the prevailing emotional tone of the market.

2. **Historical Trader Data (Hyperliquid Platform)**
   - **Columns:** `account`, `symbol`, `execution_price`, `size`, `side`, `time`, `start_position`, `event`, `closedPnL`, `leverage`, etc.
   - Captures detailed trading behavior and outcomes of individual traders.

---

## ⚙️ Key Steps in the Notebook

1. **Data Integration:** Merged both datasets to align trader actions with market sentiment on corresponding dates.  
2. **Feature Engineering:** Extracted relevant indicators and transformed raw trading data into machine-learning-friendly features.  
3. **Data Scaling & Splitting:** Normalized features and split into training/testing sets for fair model evaluation.  
4. **Model Training:** Implemented and compared **five different machine learning models** to identify the most effective predictor.  
5. **Hyperparameter Tuning:** Fine-tuned the best-performing model for optimal accuracy and generalization.  
6. **Deep Learning Integration:** Leveraged **TensorFlow** and **Keras** for building and testing neural network architectures, comparing their performance with traditional ML models.

---

## 🧮 Technologies Used

- **Python**
- **TensorFlow**, **Keras**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **Scikit-learn**
- **Jupyter Notebook**

---

## 🏆 Results Summary

- Among the five tested models, one exhibited significantly better generalization after hyperparameter optimization.  
- Neural network architectures built using **TensorFlow/Keras** provided competitive performance and revealed deeper non-linear dependencies.  
- Clear correlations were observed between trader profitability and market sentiment shifts (Fear/Greed phases).  
- The final model can serve as a foundation for **algorithmic trading strategies** based on behavioral indicators.

---

## 🚀 Future Enhancements

- Integrate **real-time sentiment feeds** for live prediction.  
- Experiment with **LSTM or transformer-based models** to capture temporal dependencies in trading behavior.  
- Extend analysis to include **social media sentiment** and **on-chain activity** data.

---

## 📁 File Structure

```
├── Internshala.ipynb        # Main analysis notebook
└── README.md
```

