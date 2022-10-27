# Quora_Question_Pair_Similarlity
# Problem Statement:
Identify which questions asked on Quora are duplicates of questions that have already been asked.
# Data Overview
Original Data is Train.csv

Train.csv contains 5 columns : qid1, qid2, question1, question2, is_duplicate

Number of rows in Train.csv = 404,290

# Tasks to perform:
> Import the General libraries, NLP module, and Machine learning modules

> Load the dataset

> Text Preprocessing: Removing html tags, Removing Punctuations, Performing stemming, Removing Stop words, Expanding contractions etc.

> Apply Tokenization, Stemming, Lemmatization

> Feature Extraction

> Text to Numerical vector conversion:
  > Apply BOW
  > Apply TFIDF vectorizer
  > Apply Word2Vector vectorizer
  > Apply Glove

> Data preprocessing

> Model Building

> Evaluate the model

> Confusion Matrix

> Classification report

> Track your experiments with the help of MLFlow

> Break your code into production ready script

# Streamlit App link: https://newquoradq.herokuapp.com/
