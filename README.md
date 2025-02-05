# CyberBullying-Tweets-Classification
This project focuses on detecting and classifying cyberbullying content on social media platforms using Support Vector Machine (SVM) and TextBlob for sentiment analysis. The text data is preprocessed and vectorized, followed by training an SVM model to identify various forms of cyberbullying, including gender, age, religion, and ethnicity-based harassment. TextBlob is utilized for sentiment analysis to classify content as positive, negative, or neutral. The goal of this project is to build an automated system that can identify and classify harmful online content efficiently.

# Key Features:
Preprocessing: Text data is preprocessed by tokenizing, removing stop words, punctuation, and applying lemmatization.
Vectorization: Utilized TF-IDF Vectorizer to convert text data into numerical vectors.
Model Training: The project explores classifiers like Support Vector Machines (SVM) to identify cyberbullying types.
Sentiment Analysis: Used TextBlob to analyze sentiments and classify text as positive, negative, or neutral.
Evaluation: Model performance was evaluated using accuracy, precision, recall, and confusion matrix metrics.

# Dataset link: 
https://storage.googleapis.com/kaggle-data-sets/1869236/3053020/compressed/cyberbullying_tweets.csv.zip?X-Goog-Algorithm=GOOG4-RSA-SHA256&X-Goog-Credential=gcp-kaggle-com%40kaggle-161607.iam.gserviceaccount.com%2F20250205%2Fauto%2Fstorage%2Fgoog4_request&X-Goog-Date=20250205T051157Z&X-Goog-Expires=259200&X-Goog-SignedHeaders=host&X-Goog-Signature=1ad71a7c4b6877822655271c4f694f39a7fd868ed4f88b0ca0e0b625430f43cf7d702603274c8c17f6659c09fed5f68ed381f82e9f28eff39202fe6e7ac21f1c82066bbe3d0fa61840c1032441877d53173f624ac2b4f50c905c7c138dd5b35bd7c75421039fb328229489d3893018eb93a416d8d173ff140037cf0949827397202076f1eb08ca9d9386e40204fbd3df4d61e7b4a53b79e2cf9e89442dff45df7052a9dd3e0652de3860019b7cf9ca1d7785d015e9de0b4f2d1ed0356877b5eab35a15d63b523507def6894dbac922d5009155515ca18631f5552a09870439503216a8ed1b61684c4a044666d836c64c67984ff1969ff2a64b77df137a992106
