# 🛒 Fake Product Review Detection 

> **An end-to-end Natural Language Processing (NLP) project to detect fake vs genuine product reviews using Machine Learning techniques.**

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![NLP](https://img.shields.io/badge/NLP-Text%20Classification-success)
![ML](https://img.shields.io/badge/Machine%20Learning-Logistic%20Regression-orange)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

---

## 📌 Overview | Fake Review Detection using NLP

Online product reviews strongly influence consumer decisions, but **fake reviews** distort trust and mislead buyers.
This project builds a **machine learning–based fake product review detection system** that classifies reviews as **fake or genuine** using **Natural Language Processing (NLP)** techniques.

### ✨ Why this project?

* Fake reviews impact **e-commerce credibility**
* Real-world NLP classification problem
* Ideal for **ML / NLP portfolios & academic projects**

**Keywords:** fake review detection, NLP project, text classification, TF-IDF, logistic regression, Amazon reviews, machine learning NLP

---

## 🧠 Technologies Used

### 🔧 Programming & Libraries

* **Python**
* **pandas, numpy** – data handling
* **scikit-learn** – ML models & evaluation
* **textblob** – basic NLP utilities
* **matplotlib, seaborn** – visualization
* **wordcloud** – textual insights

### 🛠 Tools

* Jupyter Notebook
* Google Colab

---

## 📊 Dataset | Amazon Product Reviews

The dataset consists of Amazon product reviews labeled as **fake** or **genuine**.

### 🧾 Dataset Schema

| Column     | Description                       |
| ---------- | --------------------------------- |
| `category` | Product category                  |
| `rating`   | User rating (1–5)                 |
| `label`    | Review label (`fake` / `genuine`) |
| `text_`    | Review text                       |

---

## ⚙️ Model & Pipeline Overview

The project implements a **Logistic Regression–based NLP pipeline**.

### 🔄 Workflow

1. **Data Preprocessing**

   * Remove null and duplicate reviews
   * Text cleaning (lowercasing, punctuation removal)

2. **Feature Engineering**

   * TF-IDF Vectorization
   * Conversion of text into numerical representations

3. **Model Training**

   * Logistic Regression classifier
   * Train-test split

4. **Model Evaluation**

   * Accuracy score
   * Confusion Matrix
   * Classification Report
   * ROC–AUC Curve

---

## 📈 Model Performance

| Metric    | Score  |
| --------- | ------ |
| Accuracy  | ~92%   |
| Precision | High   |
| Recall    | High   |
| ROC-AUC   | Strong |

### 🔍 Observations

* TF-IDF effectively captures review semantics
* Logistic Regression performs well on sparse text data
* Balanced performance across fake and genuine classes

---

## 🚀 How to Run the Project

### 🔑 Prerequisites

* Python **3.8+**
* pip

### 📥 Installation & Execution

```bash
# Clone the repository
git clone https://github.com/Indhu375/Fake_Product_Review_Detection.git

# Navigate to project directory
cd Fake_Product_Review_Detection

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter Notebook
jupyter notebook notebooks/Fake_Review_Detection.ipynb
```

---

## 📁 Project Structure

```
Fake_Product_Review_Detection/
│
├── data/
│   └── reviews.csv
│
├── notebooks/
│   └── Fake_Review_Detection.ipynb
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

## 🔥 Future Enhancements

* 🤖 Use **BERT / DistilBERT** for deep learning–based text classification
* 🌐 Deploy a **Streamlit web app** for real-time fake review prediction
* 📦 Train on **multiple e-commerce datasets** for better generalization
* 🧠 Add **Explainable AI (LIME / SHAP)** for transparency

---

## 🤝 Contributing

Contributions are welcome! 🎉

1. Fork the repository
2. Create a new branch

   ```bash
   git checkout -b feature/NewFeature
   ```
3. Commit changes

   ```bash
   git commit -m "Add New Feature"
   ```
4. Push to GitHub and open a Pull Request

---

## 👩‍💻 Author

**Indhu Sri S**
Aspiring Data Scientist | NLP & Machine Learning Enthusiast

🔗 GitHub: [Indhu375](https://github.com/Indhu375)

---

⭐ If you found this project useful, please **star the repository** to support the work!
