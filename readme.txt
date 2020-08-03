I have use Cornell University Movie Revie polarity dataset v2.0 from http://www.cs.cornell.edu/people/pabo/movie-review-data/ to build a classification model where I have predicted positive/negative based on text content alone.
the file has been saved and preprocessed as a tab seperated file in the same folder.
used naive Bayes and linear Support Vector Classifier after TFIDF vectorizer to build the pipeline.

both models produce almost the same accuracy score.
TFIDF vectorizer does not filter stop words, adding stop word removal can add to the processing speed when working on relatively large data.
Sentimental analysis can be used to dive deeper into understanding each review.