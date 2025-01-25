# sentiment-restaurant-reviews

This repository contains a complete pipeline for sentiment analysis, specifically applied to restaurant review data. The main steps are:
    Data Loading and Inspection: Reading a TSV file with reviews and labels.
    Text Preprocessing:\n
        Regular expression-based cleaning.
        Lowercase conversion.
        Tokenization and stemming using nltk.
        Stopword removal (carefully excluding "not" to preserve negation).
    Feature Engineering: Transforming the cleaned text into numerical data using the Bag of Words model (CountVectorizer) with a feature limit of 1500.
    Model Training and Evaluation: Training a Gaussian Naive Bayes classifier and evaluating with accuracy score.
This example showcases common NLP steps and illustrates the process of building a machine-learning model for text data.
