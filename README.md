# Sentiment Analysis of Movie Reviews

This project performs sentiment classification of IMDb movie reviews using machine learning models. The task is to classify each review as **positive** or **negative**.

---

## 📊 Dataset
- **Source:** [IMDb Dataset of 50K Movie Reviews](https://www.kaggle.com/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)  
- **File Used:** `IMDB Dataset.csv`  
- **Size:** 50,000 reviews  
- **Labels:**
  - `positive` → 1
  - `negative` → 0

---

## 🔧 Methodology
1. **Data Preprocessing**
   - Removed HTML tags and punctuation.
   - Converted text to lowercase.
   - Removed stopwords using NLTK.
   - Created a cleaned review column.

2. **Feature Engineering**
   - Applied **TF-IDF Vectorization** with max 5000 features.

3. **Model Training**
   - Trained the following models:
     - Logistic Regression
     - Naive Bayes
     - Support Vector Machine (SVM)

4. **Evaluation**
   - Metrics: Accuracy, F1-score
   - Confusion matrix visualizations for each model.
   - Classification report for Logistic Regression.

---

## 📈 Results
- All three models achieved strong performance, with **Logistic Regression** and **SVM** providing the best results.
- Example Metrics:
  - Logistic Regression → High Accuracy & F1-score
  - Naive Bayes → Fast but slightly less accurate
  - SVM → Comparable to Logistic Regression

---

## 🛠️ Libraries Used
- `pandas`, `numpy`
- `scikit-learn`
- `nltk`
- `matplotlib`, `seaborn`

---

## 🚀 Key Insights
- Text preprocessing (cleaning + stopword removal) significantly improves results.
- Logistic Regression and SVM are highly effective for binary sentiment classification tasks.

---
