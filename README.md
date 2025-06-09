# 📰 Fake News Detection with Unsupervised Learning  
*Advanced Data Science Final Project (CSCI 4022)*  
**John Danekind & Daniel Hatakeyama**

---

## 📌 Project Overview

This project explores the effectiveness of **unsupervised learning methods**—specifically clustering techniques like **K-Means with TF-IDF** and **MinHash with Jaccard distance**—in detecting fake news without using labeled data.

While most fake news detection systems rely on large, supervised models, we ask a simpler question:  
**Can document similarity alone separate real news from fake?**

To benchmark our unsupervised approaches, we also compare them with a lightweight **logistic regression** classifier.

---

## 🔍 Methods Used

- **Data Source:** Kaggle’s Fake and Real News Dataset  
- **Techniques:**
  - Text cleaning and preprocessing
  - TF-IDF vectorization and PCA
  - Jaccard distance with custom MinHash implementation
  - K-Means clustering (unsupervised)
  - Logistic regression (supervised baseline)

---

## 🧪 Key Takeaways

- **TF-IDF + KMeans** showed modest accuracy (~62%) in distinguishing fake vs. real articles.
- **MinHash + Jaccard** struggled to provide meaningful separation.
- **Logistic Regression** achieved much higher performance (~96%) using labels.
- Unsupervised methods may still offer value as fast, low-cost filters in label-scarce environments.

---

## ⚙️ Setup

Create the environment manually:
```bash
conda create -n ads_final_project_env python=3.12
