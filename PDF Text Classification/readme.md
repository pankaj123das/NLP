# PDF Text Classification
### Project Overview
This project aims to classify product PDFs into one of the four categories: Lighting, Fuses, Cables, or Others. The task involves extracting text from PDFs, preprocessing the text, and developing a machine learning model to predict the class of the product type.
### Approach
#### Data Extraction:
- The URL of the PDF are read as an user input.
- For input URL PDF text are extracted using PyMuPDF
#### Text Cleaning and preprocessing:
- Stop words are removed from the text using a predefined list of stop words.
- Remove punctuation and special characters
- The text is tokenized into words for further analysis.
#### Classification modeling:
- Tf-Idf Vectorizer is used for text Vectorization
- For Classification, I used Naive Bayes classifier Multinomial and Compliment Naive bayes and in SVM I used linear SVC
- For accuracy metric I used accuracy score, precision, recall, f1-score

### How to Run the Script
#### Prerequisites
Ensure you have the following dependencies installed:
- Python 3.6 or higher
- pandas
- requests
- nltk
- fitz  # PyMuPDF
- BytesIO
### important libraries
- *import nltk*
- *import requests*
- *import fitz*
- *from io import BytesIO*
- *import pandas as pd*
- *import re*
- *from nltk.corpus import stopwords*
- *from nltk.stem import WordNetLemmatizer*
- *from nltk.tokenize import word_tokenize*
- *import matplotlib.pyplot as plt*
- *from sklearn.feature_extraction.text import TfidfVectorizer*
- *from sklearn.pipeline import Pipeline*
- *from sklearn.naive_bayes import MultinomialNB, ComplementNB* 
- *from sklearn.svm import LinearSVC*
- *from sklearn.metrics import accuracy_score, classification_report*

### Running the Script
- Clone the repository to your local machine.
- train_data: CSV file comprising two columns, serving as your training dataset.
- test_data: CSV file comprising two columns, serving as your test dataset.


