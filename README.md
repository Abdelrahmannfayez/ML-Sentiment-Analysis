# ML-Sentiment-Analysis
performing sentiment analysis on comments using various machine learning algorithms. The goal of this project is to classify text data into positive or negative sentiment categories.

# Preprocessing
The preprocessing stage involves loading and cleaning the text data. It includes tokenization, removing stopwords, punctuation marks, and applying stemming.

# Feature Extraction
In the feature extraction stage, the text data is transformed into a numerical format that can be used for machine learning algorithms. The TF-IDF vectorization technique is employed to convert the text data into a matrix of TF-IDF features.

# Modeling
The modeling stage includes building and evaluating different machine learning models for sentiment classification. The following models are implemented:

1) Multinomial Naive Bayes
2) Support Vector Machines (SVM) 
3) Logistic Regression using both One-vs-Rest (OvR) and One-vs-One (OvO) strategies
The accuracy, classification report, and confusion matrix are calculated for each model on both training and testing data.

# Wordcloud
The result visualization section uses WordCloud to generate visual representations of the most frequent words in the text data. This provides insight into the content of the text data and the words contributing to positive and negative sentiment.

# Usage 
Place your positive text files in the pos directory and negative text files in the neg directory.
Run the code provided in the repository to perform sentiment analysis on the text data.
The code will preprocess the data, extract features, build and evaluate models, and generate WordCloud visualizations.
Note that the accuracry reached 81%. 

