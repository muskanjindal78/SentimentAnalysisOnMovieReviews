# SentimentAnalysisOnMovieReviews

## Dataset Description
Predict sentiment of movie reviews.

### Files
train.csv - the training set containing the review sentiment along with other features.
test.csv - the test set, has review features, but no sentiment column, since it is the target.
movies.csv - the file with metadata on movies.

### Columns
movieid - named id of the movie
sentiment - indicating "POSITIVE" or "NEGATIVE", which is the target.
Other columns are self explanatory.

## Description
In this dataset each record represents a movie-review pair with movie title, description, genres, duration, director, actors, users' ratings, review text, reviewer name, etc. Your task is to build an ML model to predict sentiment of the review text.

## Evaluation
F1 score micro

## Prediction Score

Logistic Regression - 0.52311
Dummy Classifier - 0.6684
