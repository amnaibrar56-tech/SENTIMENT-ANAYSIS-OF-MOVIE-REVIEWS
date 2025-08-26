# SENTIMENT-ANAYSIS-OF-MOVIE-REVIEWS
## Overview
This project builds a **machine learning model** to classify IMDb movie reviews as **positive** or **negative**.  
The goal is to apply text preprocessing, extract features, and train models such as **SVM, Naïve Bayes, or Logistic Regression** to evaluate sentiment.

## Dataset
- **Source:** [IMDb Movie Reviews Dataset](https://www.kaggle.com/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)  
- Contains **50,000 reviews** labeled as **positive** or **negative**.  
- Balanced dataset with 25k positive and 25k negative reviews.  

## ⚙️ Methodology
1. **Text Preprocessing**
   - Lowercasing, punctuation & HTML removal.  
   - Tokenization & stopword removal.  
   - Lemmatization for reducing words to base form.  

2. **Feature Extraction**
   - Used **TF-IDF Vectorization** to convert text into numerical features.  

3. **Model Training**
   - Trained and compared the following classifiers:
     - Logistic Regression  
     - Naïve Bayes  
     - Support Vector Machine (SVM)  

4. **Evaluation Metrics**
   - Accuracy  
   - F1-Score  
   - Classification Report  

## Results
- **Logistic Regression** and **SVM** achieved the best performance with high accuracy and balanced F1-scores.  
- **Naïve Bayes** was lightweight but slightly less accurate.  

## Tech Stack
- **Language:** Python  
- **Libraries:** pandas, numpy, scikit-learn, nltk  

## Future Improvements
- Apply **deep learning models** (LSTM, GRU, BERT).  
- Add **word embeddings** (Word2Vec, GloVe).  
- Deploy as a **web app** for real-time sentiment analysis.  

---

### 🔗 Author
Developed as part of a **Machine Learning project** to explore text classification and NLP.
