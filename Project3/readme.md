# Sentiment Analysis on Product Reviews

## Overview
This Jupyter Notebook, `SentimentAnalysisonProductReviews.ipynb`, focuses on applying Natural Language Processing (NLP) techniques to classify customer product reviews by sentiment. The project aims to categorize reviews as positive, negative, or neutral, providing valuable insights into customer satisfaction and product perception.

## Dataset
The dataset used for this project is sourced from Kaggle, containing millions of Amazon product reviews with the following features:

- `class`: Sentiment label (e.g., 2 = positive, 1 = negative)
- `title`: The title of the review
- `description`: Detailed customer feedback

### Sample Data
| class | title                           | description                                                                 |
|-------|---------------------------------|-----------------------------------------------------------------------------|
| 2     | Stuning even for the non-gamer  | This soundtrack was beautiful! It paints the ...                            |
| 1     | Don’t do it!!                   | The high chair looks great when it first come...                           |
| 2     | Makes My Blood Run Red-White... | I agree that every American should read this...                             |

## Project Focus
The goal of this project is to leverage NLP to classify the sentiment of product reviews accurately.

## Key Skills and Techniques
- **Text Preprocessing**: Tokenization, lemmatization
- **Feature Extraction**: TF-IDF, Word2Vec
- **Sentimental Analysis** : TextBlob
- **Classification**: Algorithms such as Naive Bayes and SVM

## Tools and Libraries
- **Python**: Pandas, Scikit-learn, NLTK, TextBlob
- **Word Embeddings**: Word2Vec

## GitHub Repository
The project files are available here: [DS-Innovators-Hub--Internship/Project3](https://github.com/AbdullahJaffrey/DS-Innovators-Hub-----Data-World--Internship/tree/main/Project3).

## Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/AbdullahJaffrey/DS-Innovators-Hub-----Data-World--Internship.git
