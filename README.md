# 🐦 Social Media Sentiment Analysis

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SowmyaGooty/SentimentAnalysis/blob/main/Social_Media_Sentiment_Analysis.ipynb)

## 📌 Overview

A Natural Language Processing (NLP) project that performs **sentiment analysis on Twitter data** to classify tweets as positive or negative. The project involves complete text preprocessing, feature extraction using Bag of Words, and classification using Logistic Regression.

---

## 📊 Dataset

- **Source:** Twitter Sentiments Dataset
- **Size:** 31,962 tweets
- **Features:** `id`, `label`, `tweet`
- **Labels:** 0 = Non-Racist/Sexist, 1 = Racist/Sexist

---

## 🔬 Methodology

### 1. Exploratory Data Analysis (EDA)
- Analyzed tweet distribution across sentiment classes
- Visualized word frequencies using word clouds
- Examined most common words per sentiment class

### 2. Text Preprocessing
- Removed **@user mentions** using regex
- Removed **special characters** and punctuation
- Converted text to **lowercase**
- Removed **short words** (length ≤ 3)
- Applied **stemming** using NLTK's PorterStemmer
- Built **Bag of Words** features using CountVectorizer

### 3. Model Training
- Split data into **training and test sets**
- Trained a **Logistic Regression** classifier
- Evaluated using **F1 Score** and **Accuracy**

---

## 📈 Results

| Metric | Score |
|---|---|
| F1 Score | Computed on test set |
| Accuracy | Computed on test set |

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![NLTK](https://img.shields.io/badge/NLTK-154f3c?style=flat)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=flat)
![Google Colab](https://img.shields.io/badge/Colab-F9AB00?style=flat&logo=googlecolab&logoColor=white)

**Libraries Used:**
- `pandas`, `numpy` — Data manipulation
- `matplotlib`, `seaborn` — Data visualization
- `nltk` — Natural language processing & stemming
- `sklearn.linear_model.LogisticRegression` — Classification model
- `sklearn.metrics` — F1 Score and Accuracy evaluation
- `re`, `string` — Text cleaning

---

## 🚀 How to Run

1. **Clone the repository**
```bash
git clone https://github.com/SowmyaGooty/SentimentAnalysis.git
```

2. **Open in Google Colab**
   - Click the "Open in Colab" badge above
   - Upload the `Twitter Sentiments.csv` dataset
   - Run all cells

3. **Or run locally**
```bash
pip install pandas numpy matplotlib seaborn scikit-learn nltk
jupyter notebook Social_Media_Sentiment_Analysis.ipynb
```

---

## 📁 Project Structure

```
SentimentAnalysis/
│
├── Social_Media_Sentiment_Analysis.ipynb  # Main notebook
└── README.md                              # Project documentation
```

---

## 🎯 Key Features

- ✅ Complete **NLP preprocessing pipeline** — cleaning, stemming, vectorization
- ✅ **31,962 tweets** analyzed
- ✅ **Word cloud visualizations** for each sentiment class
- ✅ **Logistic Regression** classifier with F1 and Accuracy evaluation
- ✅ End-to-end sentiment classification pipeline

---

## 👩‍💻 Author

**Sowmya Gooty**  
MS Engineering Data Science @ University of Houston  
📧 sgooty@cougarnet.uh.edu  
🔗 [LinkedIn](https://linkedin.com/in/sowmyagooty) | [GitHub](https://github.com/SowmyaGooty)

---

⭐ If you found this project useful, please consider giving it a star!
