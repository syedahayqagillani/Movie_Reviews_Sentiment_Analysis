#  Sentiment Analysis of Movie Reviews

This project applies **Sentiment Analysis** on the **IMDb Movie Reviews Dataset (50K reviews)** to classify movie reviews as **positive** or **negative**. The goal is to build and evaluate machine learning models that can understand text sentiment effectively.

---

## 📂 Dataset

* **Source**: [IMDb Dataset of 50K Movie Reviews](https://www.kaggle.com/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)
* Balanced dataset with 25K positive and 25K negative reviews.

---

## 🛠️ Project Workflow

1. **Text Preprocessing**

   * Tokenization
   * Removing stopwords
   * Lowercasing text
   * Removing punctuation and special characters

2. **Model Training**

   * Logistic Regression
   * Naïve Bayes
   * Support Vector Machine (SVM)

3. **Evaluation Metrics**

   * Accuracy
   * F1-Score

---

## 📊 Results

* Models were evaluated and compared using **accuracy** and **F1-score**.
* Logistic Regression and SVM achieved competitive results for sentiment classification.

---

## 🚀 How to Run

1. Clone this repository

   ```bash
   git clone https://github.com/syedahayqagillani/Movie_Reviews_Sentiment_Analysis
   cd sentiment-analysis-movie-reviews
   ```

2. Install dependencies

   ```bash
   pip install -r requirements.txt
   ```

3. Run the script

   ```bash
   python sentiment_analysis.py
   ```

---

## 📦 Requirements

* Python 3.x
* scikit-learn
* pandas
* numpy
* nltk

---

## 📌 Future Improvements

* Try Deep Learning models (LSTM, GRU, Transformers).
* Hyperparameter tuning for better accuracy.
* Add visualization for model comparison.

---



