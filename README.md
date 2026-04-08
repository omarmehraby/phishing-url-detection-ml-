# Phishing URL Detection using Machine Learning
# 🔐 Phishing URL Detection using Machine Learning

## 📌 Overview

This project aims to detect whether a URL is **phishing or legitimate** using machine learning techniques.

Phishing attacks are a major cybersecurity threat, where malicious websites imitate trusted platforms to steal sensitive information such as passwords and credit card data.

---

## 🧪 Experimentation Process

This project was developed through multiple phases:

* **Phase 1:** Initial training on a basic dataset showed very high accuracy, indicating possible overfitting.
* **Phase 2:** Testing on a different dataset revealed poor generalization, as the model failed to detect phishing URLs correctly.
* **Phase 3:** A more representative dataset was selected, and all models were retrained to improve robustness and real-world performance.

👉 This highlights the importance of **dataset quality and generalization** in machine learning.

---

## 🧠 Methodology

* Data preprocessing and cleaning
* Feature extraction from URLs (length, symbols, structure)
* Model training using machine learning algorithms
* Performance evaluation using multiple metrics

---

## 🤖 Models Used

* Logistic Regression
* Random Forest
* (Add others if you used any)

---

## 📊 Evaluation Metrics

* Accuracy
* Precision
* Recall
* Confusion Matrix
* ROC Curve

---

## 🛠️ Technologies

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib / Seaborn
* Jupyter Notebook

---

## ▶️ How to Run

```bash
git clone https://github.com/omarmehraby/phishing-url-detection-ml-.git
cd phishing-url-detection-ml-
pip install -r requirements.txt
jupyter notebook
```

---

## 📌 Key Insight

A model that performs well on one dataset may fail completely on another.
This project demonstrates the importance of testing machine learning models on **unseen data** to ensure real-world reliability.

---

## 🚀 Future Improvements

* Deploy as a web application (Streamlit / Flask)
* Use deep learning models
* Real-time phishing detection

---

## 👨‍💻 Author

**Omar Mehraby**
