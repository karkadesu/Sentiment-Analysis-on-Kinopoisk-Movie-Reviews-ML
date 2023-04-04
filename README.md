# Sentiment-Analysis-on-Kinopoisk-Movie-Reviews-ML

<b> <h3> Classification of the Kinopoisk movie reviews (Russian) </h3> </b>

  Tasks:
1. Train a model in Python to classify reviews;
2. Develop a Django web service for entering a movie review to get its sentiment (positive, neutral, negative);
3. Make this service public.
  
  
  Kinopoisk (Russian: Кинопоиск) is a Russian online database of information related to films, TV shows including cast, production team, biographies, plot summaries, ratings, and reviews.

  The dataset has 36.6k rows containing next columns: content (string),	title (string),	grade3 (string),	movie_name (string),	part (string),	review_id (string),	author (string),	date (string),	grade10 (string),	Idx (int32). (<a href="https://huggingface.co/datasets/blinoff/kinopoisk"> source </a>)

  Sentiment Analysis of IMDb Movie datasets is done using two different machine learning algorithm:
    1) Logistic Regression
    2) Linear Support Vector Classifier (LinearSVC)
  Precision score for LR is 0.8187441407395805 and 0.8139459980739157 for LinearSVC. Such negligible difference can be explained by the fact that, when exclusively using binary features with a binary outcome predictor, a LR model without regularisation and SVC with linear kernel are exactly the same.  (<a href="https://towardsdatascience.com/support-vector-classifiers-and-logistic-regression-similarity-97ff06aa6ec3]"> source </a>)


