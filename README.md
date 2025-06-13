
---

## 📊 Dataset

- **Source**: [UCI SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)
- **Format**: Each row has a label (`ham` or `spam`) and a message

---

## 🧠 Model Information

- **Preprocessing**:
  - Lowercasing
  - Removing numbers & punctuation
- **Vectorization**:
  - TF-IDF Vectorizer
- **Model Used**:
  - Multinomial Naive Bayes / Logistic Regression (changeable)
- **Accuracy Achieved**:
  - ~98% on validation set

---

## 🎨 Gradio UI Features

- 🎯 Real-time prediction
- 💬 Simple, clean input textbox
- ✨ Lottie-based animation for visual feedback
- 🖥️ Mobile-friendly interface
- 🚀 Deployable on Hugging Face or Colab

---

## 🚀 Run in Google Colab

Click the badge to open the project in Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)

---


## 🧪 How to Use

1. Clone this repository or open the notebook in Colab
2. Install dependencies:
   ```python
   !pip install gradio
   
---

Load the model and vectorizer:
import pickle
model = pickle.load(open("spam_model.pkl", "rb"))
vectorizer = pickle.load(open("vectorizer.pkl", "rb"))

---
