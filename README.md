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


Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the notebook or script:

Use the .ipynb version for step-by-step

Or run the .py file for full pipeline

🧪 Evaluation Results (Example)
Model	Accuracy	F1-Score (Macro)	AUC
Naive Bayes	72.5%	0.71	0.85
Logistic Regression	81.2%	0.80	0.91
SVM	83.0%	0.82	—

 Visualizations
Confusion matrices for all models

PCA scatter plot of TF-IDF vectors

 PR curve


Methodology
This project follows the CRISP-DM data mining methodology:

Business Understanding

Data Understanding

Data Preparation

Modeling

Evaluation


References
scikit-learn documentation: https://scikit-learn.org/

CRISP-DM model: https://www.datascience-pm.com/crisp-dm-2/

