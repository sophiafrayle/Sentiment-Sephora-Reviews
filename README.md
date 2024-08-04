## Portfolio Project: Review Sentiment Analysis

### Project Overview

This project is a comprehensive analysis of customer reviews to determine the sentiment expressed in them. The primary goal is to leverage Natural Language Processing (NLP) techniques to classify reviews as positive, negative, or neutral, providing valuable insights into customer opinions.

### Objectives

- **Data Collection**: Gather customer reviews from a relevant source.
- **Data Preprocessing**: Clean and prepare the data for analysis.
- **Sentiment Analysis**: Implement NLP techniques to analyze the sentiment of the reviews.
- **Model Evaluation**: Assess the performance of the sentiment analysis models.
- **Insights and Visualization**: Present the findings through visualizations and interpret the results.

### Data Collection

The data for this project is sourced from [Kaggle](https://www.kaggle.com/datasets/nadyinky/sephora-products-and-skincare-reviews?select=reviews_0-250.csv). The dataset includes customer reviews, ratings, and additional metadata relevant to the analysis.

### Data Preprocessing

1. **Cleaning**: Remove irrelevant information such as HTML tags, special characters, and stop words.
2. **Tokenization**: Break down the text into individual tokens or words.
3. **Normalization**: Convert all text to lowercase and lemmatize the words to their base forms.
4. **Vectorization**: Transform the text data into numerical vectors using techniques such as TF-IDF or word embeddings.

### Sentiment Analysis

Several machine learning models and NLP techniques are employed to classify the sentiment of the reviews:

- **TextBlob**: A simple library for sentiment analysis.
- **VADER (Valence Aware Dictionary and sEntiment Reasoner)**: A lexicon and rule-based sentiment analysis tool.
- **Machine Learning Models**: Implement models such as Logistic Regression, Support Vector Machines (SVM), and Naive Bayes.
- **Deep Learning Models**: Utilize neural networks like LSTM (Long Short-Term Memory) for more complex sentiment analysis.

### Model Evaluation

The performance of the sentiment analysis models is evaluated using metrics such as accuracy, precision, recall, and F1-score. Cross-validation is also performed to ensure the robustness of the models.

### Insights and Visualization

The results of the sentiment analysis are presented through various visualizations:

- **Sentiment Distribution**: Pie charts or bar graphs showing the proportion of positive, negative, and neutral reviews.
- **Word Clouds**: Highlighting the most frequent words in positive and negative reviews.
- **Trend Analysis**: Line graphs to show sentiment trends over time or in response to specific events.

### Conclusion

This project provides a detailed understanding of customer sentiments through reviews. The insights derived can help businesses improve their products and services, enhance customer satisfaction, and make informed decisions.

### Future Work

- **Expansion to Multilingual Analysis**: Extend the sentiment analysis to reviews in multiple languages.
- **Aspect-Based Sentiment Analysis**: Identify sentiment towards specific aspects of a product or service.
- **Integration with Real-Time Systems**: Implement the sentiment analysis models in a real-time system to monitor customer feedback continuously.


### Author

![Signature](https://github.com/sophiafrayle/EDA-Covid/blob/main/images/Sophia%20Frayle.png)
