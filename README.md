# 📰 Fake News Detection Using Naive Bayes

## 📖 Overview

This project aims to tackle the growing challenge of misinformation by building a machine learning model that distinguishes between **fake and real news articles**. By applying **Natural Language Processing (NLP)** techniques and **Naive Bayes classifiers**, we demonstrate how machine learning can be used to combat digital misinformation effectively.

---

## 🎯 Objective

To build a classifier that accurately identifies whether a given news article is **fake or genuine** based on its textual content, with an extended focus on sentiment-bearing text sources such as **tweets, blogs, speeches, and reviews**.

---

## 🛠️ Technologies Used

- **Programming Language**: Python  
- **Libraries**: `pandas`, `numpy`, `scikit-learn`, `NLTK`  
- **NLP Techniques**: 
  - Tokenization  
  - Stop word handling  
  - Negation handling  
  - Vectorization (Bag of Words)  
- **Models Used**: 
  - Boolean Naive Bayes  
  - Multinomial Naive Bayes  
- **Evaluation Metrics**: 
  - Accuracy  
  - Precision  
  - Recall  
  - F1 Score  

---

## 🔍 Methodology

### 🔧 Data Preprocessing
- Cleaned text data and handled **negations** (e.g., “not good” treated as a unified token).
- Experimented with the **inclusion/exclusion of stop words** to measure impact.
- Applied **vectorization (bag-of-words)** to convert text into numerical features.

### 🧠 Model Training
- Trained two models: **Boolean Naive Bayes** and **Multinomial Naive Bayes**.
- Compared performance of both using multiple evaluation metrics.

### 📊 Evaluation
- Computed **Accuracy**, **Precision**, **Recall**, and **F1 Score**.
- Visualized results with confusion matrices and metric charts for clarity.

---

## ✅ Results

- The classifier achieved high performance in distinguishing **fake** from **real** articles.
- Preprocessing steps like **negation handling** and **stop word removal** significantly improved prediction accuracy.
- **Multinomial Naive Bayes** performed slightly better than Boolean Naive Bayes on the provided dataset.

---

## 💡 Key Takeaways

- NLP **preprocessing**, especially **negation handling**, plays a critical role in classification accuracy.
- Simple models like **Naive Bayes** are effective for baseline text classification tasks.
- This project provides a foundation for **advanced fake news detection systems**, including deep learning or real-time applications.

---


