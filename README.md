## Sentiment Analysis using Naive Bayes

The goal of the project is to create a text indexing pipeline for Amazon user reviews based on Spark ML library
Here we are going to create a text indexing pipeline for user reviews based on Spark ML library.

### Dataset
The dataset was available in JSON format which was loaded into a dataframe for analysis

### Analysis
The target variable called label (posititive/negative) was created based on the rating for each review in the dataset. The features
were obtained from the text indexing pipeline using TF-IDF aaproach and Naive Bayes cleassifier was used to classify between positive
and negative reviews



