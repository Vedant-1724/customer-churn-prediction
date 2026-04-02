# 🔄 Customer Churn Prediction System

An end-to-end machine learning project that predicts whether a customer will leave a telecom company, built using Python and XGBoost.

---

## 📊 Results

| Model | Accuracy | Churn Recall |
|---|---|---|
| Random Forest | 79.2% | 49% |
| Random Forest (Balanced) | 78.3% | 45% |
| XGBoost ✅ | 72.2% | **79%** |

- ✅ Catches **4 out of 5** customers who will actually churn
- ✅ Predicts high-risk customers with **92.4% confidence**
- ✅ Reduced missed churners from **191 → 80**

---

## 🛠️ Tech Stack

Python | XGBoost | Scikit-learn | Pandas | Matplotlib | Google Colab

---

## 📁 Dataset

[Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) — 7,043 customer records from Kaggle

---

## 🚀 How to Run

1. Open `Cust_churn.ipynb` in Google Colab
2. Upload the Telco dataset CSV file
3. Run all cells in order
4. Model gets saved to your Google Drive automatically

---

## 💡 Key Learnings

- XGBoost outperforms Random Forest on imbalanced datasets
- Recall matters more than accuracy in churn prediction
- `scale_pos_weight` is key for handling class imbalance
