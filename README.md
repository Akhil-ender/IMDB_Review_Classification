# Sentiment Classification of IMDB Movie Reviews
This project focuses on sentiment classification of IMDB movie reviews using natural language processing (NLP) and machine learning techniques. The objective is to predict whether a given movie review is positive or negative based on the content of the review.

## Project Overview:
- Dataset: IMDB Movie Reviews dataset (https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews).
- Task: Sentiment classification (binary classification: positive/negative).
- Model: Logistic Regression (with TF-IDF features and hyperparameter tuning).

## Steps Involved:
### Data Preprocessing:
- Removal of HTML tags.
- Conversion of text to lowercase.
- Removal of special characters, digits, and punctuation.
- Tokenization and removal of stopwords.
- Lemmatization of tokens to obtain root words.
  
### Feature Extraction:
- TF-IDF (Term Frequency-Inverse Document Frequency): Extracts features from text and converts them into a numerical format.

### Model Training:
- Logistic Regression: A simple and effective model for binary classification.
- Hyperparameter tuning using GridSearchCV to optimize regularization strength (C), solver, and max iterations.

### Model Evaluation:
- Accuracy, precision, recall, and F1-score metrics used to evaluate model performance.

