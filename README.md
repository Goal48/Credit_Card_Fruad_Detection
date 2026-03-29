# 💳 Credit Card Fraud Detection using Machine Learning

## 📌 Project Overview

Credit card fraud is a major issue in the financial industry, leading to significant financial losses every year. This project aims to build a robust **machine learning model** to detect fraudulent transactions using real-world transaction data.

The model identifies suspicious patterns and classifies transactions as **fraudulent or legitimate**, helping improve security and reduce financial risk.

---

## 🚀 Key Features

* 🔍 Exploratory Data Analysis (EDA)
* ⚖️ Handling Imbalanced Dataset
* 🤖 Model Training using XGBoost
* 📊 Performance Evaluation (Precision, Recall, ROC-AUC)
* 📉 Feature Importance Analysis

---

## 📊 Dataset Information

* Source: Kaggle Credit Card Fraud Dataset
* Total Transactions: 284,807
* Fraud Cases: 492 (Highly Imbalanced ⚠️)
* Features:

  * `V1–V28`: PCA transformed features
  * `Time`, `Amount`
  * `Class` → Target (0 = Normal, 1 = Fraud)

---

## 🧠 Machine Learning Approach

### 🔹 Steps Followed:

1. Data Cleaning & Preprocessing
2. Train-Test Split
3. Handling Imbalance using `scale_pos_weight`
4. Model Training using XGBoost
5. Model Evaluation

---

## ⚙️ Model Used

* **XGBoost Classifier**

  * Handles imbalanced data effectively
  * Provides high accuracy and performance
  * Robust to overfitting

---

## 📈 Evaluation Metrics

Since the dataset is imbalanced, accuracy is not reliable.
We focus on:

* ✅ Precision
* ✅ Recall
* ✅ F1 Score
* ✅ ROC-AUC Score

---

## 📊 Results

* High recall achieved for fraud detection
* Balanced precision to reduce false positives
* ROC-AUC score shows strong model performance

*(You can add your actual score here like: ROC-AUC = 0.98)*

---

## 🛠️ Tech Stack

* Python 🐍
* Pandas, NumPy
* Scikit-learn
* XGBoost
* Matplotlib, Seaborn

---

## 📂 Project Structure

```
├── data/
├── notebooks/
├── src/
├── model/
├── README.md
└── requirements.txt
```

---

## ▶️ How to Run

```bash
# Clone the repository
git clone https://github.com/Goal48/Credit_Card_Fruad_Detection.git

# Go to project folder
cd Credit_Card_Fruad_Detection

# Install dependencies
pip install -r requirements.txt

# Run notebook / script
```

---

## 💡 Future Improvements

* Use SMOTE for better imbalance handling
* Deploy model using Streamlit / Flask
* Real-time fraud detection system
* Hyperparameter tuning for better performance

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repo and submit a pull request.

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 👨‍💻 Author

**Pius Dutta**
📧 piusdutta413@gmail.com
🔗 www.linkedin.com/in/pius-dutta-254143293
🐙 https://github.com/Goal48

---

⭐ If you like this project, don’t forget to star the repo!
