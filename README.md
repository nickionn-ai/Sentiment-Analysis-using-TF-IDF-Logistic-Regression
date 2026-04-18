# 🎬 Sentiment Analysis with Machine Learning

A machine learning project that classifies movie reviews as **positive** or **negative** using Natural Language Processing (NLP).

---

## 📌 Project Overview

This project implements a complete NLP pipeline for sentiment analysis on the IMDB dataset.

The workflow includes:
- Text preprocessing
- Feature extraction using TF-IDF
- Model training with Logistic Regression
- Model evaluation and interpretation

---

## ⚙️ Technologies Used

- Python
- Pandas & NumPy
- Scikit-learn
- Matplotlib & Seaborn

---

## 📊 Dataset

- Source: IMDB Movie Reviews Dataset
- Total samples used: 10,000
- Balanced dataset (positive / negative)

---

## 🔧 Data Preprocessing

- Lowercasing text
- Removing HTML tags
- Removing punctuation
- Cleaning raw text

---

## 🧠 Feature Engineering

We transform text into numerical features using:

- **TF-IDF Vectorization**
- Max features: 5000
- Stop words removed (English)

---

## 🤖 Model

We use:

- **Logistic Regression**
- Simple and effective baseline for text classification

---

## 📈 Model Evaluation

Performance on test data:

- Accuracy: **~86.8%**
- Precision / Recall / F1-score evaluated

### Confusion Matrix

The model performs well with relatively few misclassifications.

---

## 🔍 Explainability

We analyze model coefficients to understand:

- Words contributing to **positive sentiment**
- Words contributing to **negative sentiment**

Example:

**Positive words:**
- great, excellent, amazing

**Negative words:**
- bad, worst, terrible

---

## 🧪 Example Usage

```python
predict_sentiment("This movie was amazing, I loved it!")
# Output: Positive

predict_sentiment("Worst movie ever")
# Output: Negative
## 🚀 Future Improvements

- Use advanced models such as LSTM or BERT
- Perform hyperparameter tuning
- Deploy the model as a web app using Streamlit or Flask
- Add real-time predictions

---

## 📂 Project Structure

```text
Sentiment-Analysis-ML/
│
├── Sentiment-Analysis-ML.ipynb
├── requirements.txt
├── LICENSE
└── README.md
## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

Nikolaos Ioannidis
