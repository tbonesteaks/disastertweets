# Classify Tweets as Disaster Report or Not RNN
Can a vanilla RNN, LSTM or GRU classifier determine which tweets are disaster reports? These notebooks were to prove that yes, they can. 

The initial set of models in [disaster_tweets_classifier.ipynb](disaster_tweets_classifier.ipynb) use only lemmatization, stopword removal, and simple models to achieve accuracy rates over 75%.

The second set of models improve on the basic implementation with the use of word2vec, glove, and tf-idf and are available on request.

These models were trained using the disaster tweets competition dataset available here: [Disaster Tweets Competition](https://www.kaggle.com/competitions/nlp-getting-started)
