#  Email Spam Detection & Filtering Using NLP

This project demonstrates how Natural Language Processing (NLP) and machine learning can be applied to detect and filter spam emails. Using classic text classification techniques and a Naïve Bayes model, this project builds a lightweight, accurate spam filter capable of distinguishing between legitimate (ham) and spam messages.

---

##  Project Overview

- Preprocessed raw email data: cleaned text, removed punctuation, standardized casing
- Visualized spam vs ham messages using word clouds
- Used stemming and n-grams to improve feature representation
- Applied `CountVectorizer` with custom preprocessing for feature extraction
- Trained and evaluated a **Multinomial Naïve Bayes** classifier
- Achieved strong predictive accuracy on classifying spam emails

---

##  Techniques Used

- Natural Language Processing (NLP)
- Text Preprocessing (lowercasing, punctuation removal, stemming)
- Feature Extraction using `CountVectorizer` (uni- and bi-grams)
- Supervised Learning with Multinomial Naïve Bayes
- Model Evaluation using Accuracy Score

---

##  Results

- The classifier accurately distinguishes spam from ham messages
- Preprocessing steps like stemming and bigram modeling significantly boosted performance
- Visualizations helped understand keyword distribution in each class

---

##  Tools & Libraries

- Python
- Pandas, NumPy
- Scikit-learn
- TextBlob, NLTK
- WordCloud, Matplotlib, Seaborn

---

##  Files Included

- `Email filtering Using NLP.ipynb` – Jupyter Notebook containing full implementation
- `spam.csv` – Dataset containing labeled email messages

---

##  Future Improvements

- Implement additional models (e.g., SVM, Logistic Regression, Deep Learning)
- Perform cross-validation and hyperparameter tuning
- Deploy the model as an API or simple web app
