# Credit Card Fraud Detection using Machine Learning

## 📌 Overview
This project builds a machine learning model to detect fraudulent credit card transactions.

## ⚠️ Problem
The dataset is highly imbalanced, with very few fraudulent transactions compared to normal ones.

## ⚙️ Approach
- Data preprocessing and scaling
- Logistic Regression model
- Handling class imbalance using class weighting
- Model evaluation using precision and recall

## 📊 Results
| Model                         | Precision (Fraud) | Recall (Fraud) | Accuracy |
|------|------------------|----------------|----------|
| Logistic Regression            |0.80                   0.57               0.67  
| Weighted Logistic Regression   |0.20                   0.93               0.33 |

## 🧠 Key Insight
There is a tradeoff between precision and recall:
- High precision → fewer false alarms
- High recall → more frauds detected

In fraud detection, **recall is more important** because missing fraud is costly.

## ▶️ How to Run
1. Open notebook in Google Colab
2. Upload dataset
3. Run all cells

## 🚀 Future Improvements
- Use Random Forest / XGBoost
- Improve recall further
- Build real-time fraud detection system

## 📌 Author
Rayyan Abdul Waheed
