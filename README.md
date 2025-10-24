# Fake Product Review Detection

## 📌 Project Overview
This project detects **fake vs genuine product reviews** using **Natural Language Processing (NLP)** and **Machine Learning (ML)** techniques.  
By analyzing review text, the model classifies reviews as **fake** or **real**, helping consumers make informed purchasing decisions.

---

## 🧠 Technologies Used
- **Programming Language:** Python
- **Libraries:**
  - pandas, numpy
  - scikit-learn
  - textblob
  - matplotlib, seaborn
  - wordcloud
- **Tools:** Jupyter Notebook / Google Colab

---

## 📊 Dataset
The dataset contains Amazon product reviews with the following columns:

| Column Name | Description |
|------------|-------------|
| `category` | Product category |
| `rating`   | User-provided rating (1–5) |
| `label`    | Review label (fake / genuine) |
| `text_`    | Review text |

---

## ⚙️ Model Overview
The project uses **Logistic Regression** to classify reviews. Key steps:

1. **Data Preprocessing:** Clean text, remove nulls.
2. **Feature Extraction:** Convert text to numerical features using TF-IDF.
3. **Model Training:** Train Logistic Regression on preprocessed data.
4. **Evaluation:** Accuracy, Confusion Matrix, Classification Report, ROC-AUC.

---

## 📈 Model Performance (Example)
Accuracy: ~92%
Confusion Matrix and Classification Report displayed in notebook.
ROC-AUC score used for evaluation.


---

## 🚀 How to Run
1. Clone the repository:
   
git clone https://github.com/Indhu375/Fake_Product_Review_Detection.git

2.Navigate to project folder:

cd Fake_Product_Review_Detection


3.Install required dependencies:

pip install -r requirements.txt


4.Open the notebook:

jupyter notebook notebooks/Fake_Review_Detection.ipynb

<img width="441" height="339" alt="image" src="https://github.com/user-attachments/assets/1e560c0c-f64b-482d-88fa-c4655bbd2453" />

🔥 Optional Improvements

Use BERT / DistilBERT for better text classification.

Deploy a Streamlit web app for real-time predictions.

Include more datasets to improve generalization.
