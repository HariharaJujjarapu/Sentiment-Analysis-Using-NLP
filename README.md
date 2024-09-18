# Sentiment Analysis Using Natural Language Processing (NLP)

This project performs sentiment analysis on restaurant reviews using **Natural Language Processing (NLP)**. The goal is to classify reviews as positive or negative based on their content.

## Dataset
The dataset consists of 1,000 restaurant reviews in `.tsv` format. Each review is labeled as either **Liked** (positive) or **Disliked** (negative).

## Approach
1. **Data Cleaning**: Non-alphabetic characters are removed, and reviews are converted to lowercase and tokenized.
2. **Stopword Removal & Stemming**: Common stopwords, except "not," are removed. Stemming is applied using the Porter Stemmer to reduce words to their root forms.
3. **Feature Extraction**: Text data is converted to a numerical format using **CountVectorizer** (Bag-of-Words model).
4. **Model Training**: A **Naive Bayes classifier** is trained on the preprocessed reviews to predict sentiment.
5. **Model Evaluation**: Performance is evaluated using accuracy score and confusion matrix.

## Results
- The Naive Bayes model achieved an accuracy of **67.29%** on the test dataset.

## How to Run the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/sentiment-analysis-nlp.git

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
3. Run the Python script or Jupyter Notebook to train the model and test its accuracy.
