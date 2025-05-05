# 🧠 Twitter Topic Classification

A Natural Language Processing pipeline for multi-class classification of tweets into six topical categories using TF-IDF vectorization and machine learning models. Built for academic research and evaluation, following the CRISP-DM methodology.

---

## 📂 Dataset

The dataset contains 6,443 human-labeled tweets, each assigned to one of the following categories:

0. Arts & Culture  
1. Business & Entrepreneurs  
2. Pop Culture  
3. Daily Life  
4. Sports & Gaming  
5. Science & Technology  

Each tweet includes the raw text, date, label, and a category name.

---

## ⚙️ Features

- Preprocessing pipeline: URL removal, hashtag/mention retention, lowercasing
- Text vectorization using **TF-IDF with n-grams**
- Model training and tuning using:
  - ✅ **Naive Bayes**
  - ✅ **Logistic Regression** (`GridSearchCV` tuned)
  - ✅ **Support Vector Machine (SVM)** (`GridSearchCV` tuned)
- Visualizations:
  - 2D PCA of text features
  - Confusion matrices
  - Accuracy comparison
  - ROC & Precision-Recall curves
- Evaluation using accuracy, F1-score, AUC, and training time
- Follows the **CRISP-DM** methodology

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/twitter-topic-classification.git
   cd twitter-topic-classification
