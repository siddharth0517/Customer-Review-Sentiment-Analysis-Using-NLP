# Customer Review Sentiment Analysis Using NLP

This project applies Natural Language Processing (NLP) techniques to perform sentiment analysis on customer reviews. The goal is to classify reviews as positive or negative using machine learning algorithms.

## Project Overview

- **Objective**: To predict whether a customer review is positive or negative.
- **Dataset**: Customer reviews in TSV format.
- **Techniques**: Text preprocessing, feature extraction, and machine learning models.
- **Models Used**:
  - Logistic Regression (Accuracy: 77%)
  - Naive Bayes (Accuracy: 73%)
- **Evaluation**: Confusion Matrix and Accuracy Score

## Project Structure

- `Customer_Review_Sentimental_Analysis.ipynb`: The main Jupyter notebook containing the code for sentiment analysis.

## Steps in the Project

1. **Data Import and Preprocessing**: 
   - Loading the dataset and cleaning the text data (removing stopwords, punctuation, etc.).

2. **Feature Extraction**:
   - Using techniques like TF-IDF (Term Frequency - Inverse Document Frequency) to convert text data into numerical features.

3. **Model Building**:
   - Logistic Regression and Naive Bayes were applied to predict the sentiment of customer reviews.

4. **Model Evaluation**:
   - Logistic Regression achieved 77% accuracy.
   - Naive Bayes achieved 73% accuracy.
   - Confusion matrices were used to evaluate the performance of both models.

## Conclusion
This project demonstrates the use of NLP techniques and machine learning models (Logistic Regression and Naive Bayes) to classify customer reviews as positive or negative. **Logistic Regression performed slightly better with 77% accuracy compared to Naive Bayes' 73%.**
