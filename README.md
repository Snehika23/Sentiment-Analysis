# 🧠 Sentiment Analysis — Major Project

> **Bachelor of Technology (CSE - Data Science)**  
> NRI Institute of Technology, Vijayawada | Academic Year 2023–2024  
> Published: *Journal of Interdisciplinary Cycle Research*, Vol. XVI, Issue III, March 2024 (ISSN: 0022-1945)

---

## 📌 Project Overview

This project builds an **automated sentiment analysis system** for Amazon Fine Food Reviews, classifying customer reviews into **positive**, **neutral**, and **negative** sentiments using machine learning and NLP techniques.

With over **568,000 Amazon food reviews** in the dataset, the system uses TF-IDF vectorisation and three supervised classifiers to extract actionable insights for businesses.

---

## 📂 Repository Contents

| File | Description |
|------|-------------|
| [Final Major Project Done[1] - Snehika_Final.docx](https://github.com/Snehika23/Sentiment-Analysis/blob/main/Final%20Major%20Project%20Done%5B1%5D%20-%20Snehika_Final.docx) | Full B.Tech project report |
| [Twitter sentiment analysis.pptx](https://github.com/Snehika23/Sentiment-Analysis/blob/main/Twitter%20sentiment%20analysis.pptx) | Presentation deck (Twitter Sentiment Analysis) |
| [11-JICR-MARCH-2024.pdf](https://github.com/Snehika23/Sentiment-Analysis/blob/main/11-JICR-MARCH-2024.pdf) | Published research paper (JICR, March 2024) |

---

## 🔬 Methodology

### Pipeline
```
Data Collection → Preprocessing → EDA → Feature Extraction → Model Training → Evaluation → Visualisation
```

### Data
- **Dataset:** Amazon Fine Food Reviews (Kaggle)
- **Size:** 568,454 reviews (10+ years, up to October 2012)
- **Features:** Rating, product info, user info, plain text review

### Preprocessing
- Removed null values and duplicate entries
- Stripped punctuation, special characters, and stop words
- Applied stemming and lemmatisation
- Converted Unix timestamps to human-readable dates

### Feature Extraction
- **TF-IDF Vectorisation** — transformed text into numerical representations for model input

### Sentiment Labels
| Score | Label |
|-------|-------|
| > 3 | Positive (1) |
| = 3 | Neutral (2) |
| < 3 | Negative (0) |

---

## 🤖 Models & Results

| Model | Accuracy |
|-------|----------|
| Logistic Regression | **73.37%** |
| Random Forest | **72.65%** |
| SVM | **68.89%** |

Logistic Regression achieved the highest accuracy, making it the best-performing model for this task.

---

## 📊 Key Visualisations

- **Word Clouds** — high-polarity positive and negative terms
- **Review Length Distribution** — histogram of text lengths
- **Sentiment Distribution** — count plot of positive / neutral / negative reviews
- **Review Score Bar Chart** — distribution across 1–5 star ratings

---

## 🛠 Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)

**Libraries:** `nltk` · `sklearn` · `pandas` · `numpy` · `matplotlib` · `seaborn` · `wordcloud`  
**Algorithms:** Logistic Regression · SVM · Random Forest  
**Vectorisation:** TF-IDF

---

## 👩‍💻 Author

**A. Snehika** (20KN1A4402)  
B.Tech, Computer Science & Engineering (Data Science)  
NRI Institute of Technology, Vijayawada, Andhra Pradesh

**Project Guide:** Ch. Venkata Murali Krishna (Associate Professor, CSE-DS)

---

## 📄 Publication

> *"Exploring Emotional Terrain: A Study of Sentiment Analysis in Textual Data"*  
> Amudalapalli Snehika, Nimmakuri Chandu Tej, Yalamarthi Samyuktha, Tanikella Lakshmi Sowmya, Chinta Venkata Murali Krishna  
> **Journal of Interdisciplinary Cycle Research**, Vol. XVI, Issue III, March 2024 | ISSN: 0022-1945 | Pages 85–92

---

## 🔮 Future Scope

- Word embeddings and deep learning (BERT, LSTM) for improved accuracy
- Fine-grained and aspect-based sentiment analysis
- Real-time sentiment monitoring pipeline
- Multi-domain and multimodal data integration
