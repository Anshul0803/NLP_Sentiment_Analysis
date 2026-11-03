NLP Sentiment Classification on Customer Reviews

Project Overview

This project focuses on building a Natural Language Processing (NLP) based Sentiment Classification system that analyses customer reviews and classifies them into three sentiment categories:

* Positive
* Negative
* Neutral

The project uses text preprocessing techniques, TF-IDF vectorisation, and Machine Learning classification algorithms to identify the sentiment expressed in customer reviews.

Objectives

* Understand and implement fundamental NLP techniques.
* Clean and preprocess raw customer review data.
* Convert textual data into numerical representations using TF-IDF.
* Train Machine Learning models for sentiment classification.
* Evaluate classification models.
* Build a function to predict sentiment for new customer reviews.

Technologies Used

Technology	Purpose
Python	Programming language
Pandas	Data manipulation
NumPy	Numerical operations
Matplotlib	Data visualisation
Seaborn	Statistical visualisation
NLTK	Tokenization
spaCy	Lemmatization
Scikit-learn	Machine Learning
Jupyter Notebook	Development environment

Machine Learning Algorithms

1. Multinomial Naive Bayes: A probabilistic classification algorithm commonly used for text classification.
2. Logistic Regression: A supervised classification algorithm used to predict sentiment categories.

Project Workflow

1. Dataset Loading

* Load customer reviews from a CSV file.
* Explore dataset structure and identify missing values.

2. Text Preprocessing

* Convert text into lowercase.
* Remove HTML tags and URLs.
* Remove punctuation and special characters.
* Remove unnecessary whitespace.

3. Tokenization

* Split customer reviews into individual words.
* Preserve important negation words such as “not”, “no”, and “never”.

4. Stopword Removal

* Remove commonly occurring words that contribute limited information to sentiment classification.

5. Lemmatization

* Convert words into their meaningful base forms using spaCy.

6. Exploratory Data Analysis

* Analyse sentiment distribution.
* Calculate review lengths.
* Visualise sentiment categories and review length distributions.

7. TF-IDF Vectorisation

* Convert processed text into numerical feature vectors.
* Calculate the importance of words using Term Frequency-Inverse Document Frequency.

8. Train-Test Split

* Divide the dataset into training and testing subsets.
* Use an 80:20 split.

9. Model Training

* Train Multinomial Naive Bayes.
* Train Logistic Regression.

10. Sentiment Prediction

* Accept new customer reviews.
* Apply the same preprocessing pipeline.
* Predict the sentiment using the trained Logistic Regression model.