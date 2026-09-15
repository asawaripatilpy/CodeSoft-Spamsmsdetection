# 📱 Spam SMS Detection

A Machine Learning and Natural Language Processing (NLP) project that classifies SMS messages as Spam or Legitimate (Ham).

## 📌 Project Overview

This project uses TF-IDF to convert SMS text into numerical features and compares multiple Machine Learning classification algorithms.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- TF-IDF
- Naive Bayes
- Logistic Regression
- Support Vector Machine (SVM)
- Joblib
- Jupyter Notebook

## 🔄 Project Workflow

1. Dataset Loading
2. Data Cleaning
3. Label Encoding
4. Train-Test Split
5. TF-IDF Feature Extraction
6. Model Training
7. Model Evaluation
8. Best Model Selection
9. Spam SMS Prediction

## 🤖 Models Used

- Multinomial Naive Bayes
- Logistic Regression
- Linear Support Vector Machine

## 📊 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

## 📂 Project Structure

```text
CodeSoft-SpamSMSDetection/
│
├── notebook/
│   └── spam_sms_detection.ipynb
│
├── models/
│   ├── spam_model.pkl
│   └── tfidf_vectorizer.pkl
│
├── data/
│   └── Dataset files (not included in GitHub)
│
├── .gitignore
└── README.md
```

🎯 Objective

To automatically identify unwanted spam SMS messages using Machine Learning and NLP techniques.

🚀 Future Improvements
Build a web interface for real-time SMS classification
Try advanced NLP techniques
Experiment with word embeddings
Improve model performance