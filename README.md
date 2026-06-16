<div align="center">

# 📰 Fake News Prediction

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org)
[![NLP](https://img.shields.io/badge/NLP-Text%20Classification-9C27B0?style=for-the-badge&logo=python&logoColor=white)](https://python.org)

> **Can a machine detect fake news from just the article text?**
> An NLP-based text classification project built as part of the TNSDC Naan Mudhalvan program.

</div>

---

## 📌 Problem Statement

The rapid spread of misinformation online is a critical challenge in the digital age. This project builds a **Fake News Detection model** that analyzes the text of a news article and predicts whether it is **genuine or fake** — using Natural Language Processing (NLP) and Machine Learning classification techniques.

---

## 🎯 Project Highlights

| What | Detail |
|------|--------|
| 🧠 Type | NLP — Text Classification |
| 📦 Task | Binary Classification (Fake / Genuine) |
| 🔤 Technique | TF-IDF Vectorization + ML Classifier |
| 📊 Features | Word frequencies, linguistic patterns, sentiment |

---

## 🗂️ Project Structure

```
TNSDC-Generative_AI/
│
├── FAKE NEWS PREDICTION.ipynb   # Jupyter Notebook — full NLP pipeline
├── Naan Mudhalvan PPT.pptx      # Project presentation (TNSDC submission)
└── README.md
```

---

## 🔄 NLP Pipeline

```
Raw Text  →  Preprocessing  →  Feature Extraction  →  Model Training  →  Evaluation  →  Prediction
```

**Step-by-step:**

1. **Data Collection** — Labeled dataset of fake and genuine news articles
2. **Text Preprocessing** — Lowercasing, removing stopwords, punctuation, stemming
3. **Feature Extraction** — TF-IDF Vectorization to convert text to numerical features
4. **Model Training** — ML classifier (Logistic Regression / Random Forest / Passive Aggressive)
5. **Evaluation** — Accuracy, Precision, Recall, F1-Score
6. **Prediction** — Input news text → outputs Fake or Genuine

---

## 📊 Key Findings

- 📝 **Word frequency patterns** differ significantly between fake and genuine articles
- 🔠 **TF-IDF** effectively captures the importance of words across the corpus
- ⚡ **Passive Aggressive Classifier** performs exceptionally well on text classification tasks
- 🧹 Proper **text preprocessing** has the biggest impact on model accuracy

---

## ⚙️ How to Run

```bash
# 1. Clone the repository
git clone https://github.com/keerthanad29/TNSDC-Generative_AI.git
cd TNSDC-Generative_AI

# 2. Install dependencies
pip install pandas numpy scikit-learn matplotlib seaborn nltk

# 3. Launch Jupyter Notebook
jupyter notebook "FAKE NEWS PREDICTION.ipynb"
```

> Or open directly in **Google Colab** — no setup needed!

---

## 📦 Requirements

```
pandas
numpy
scikit-learn
matplotlib
seaborn
nltk
```

---

## 💡 What I Learned

- How to apply **NLP techniques** to solve a real-world problem
- **TF-IDF vectorization** — converting raw text into meaningful numerical features
- Why **text preprocessing** (stopword removal, stemming) is critical in NLP
- Evaluating text classifiers using **precision, recall, and F1-score**
- The societal importance of **AI in combating misinformation**

---

## 🔮 Future Improvements

- [ ] Use advanced models like BERT or DistilBERT for better accuracy
- [ ] Add a real-time news URL input for live prediction
- [ ] Build a web app using Streamlit for interactive use
- [ ] Expand dataset to include multilingual fake news detection
