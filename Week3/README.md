# CS ML Maymester'18 Week 3 Assignment: Natural Language Processing

## User Stories
[X] Build feature vectors for song lyrics in MasterSongList.json using the following NLP techniques: * Bag Of Words * TF-IDF * Doc2Vec

[X] Create classifiers that can differentiate between at least two different moods based on each of the above feature representations

[X] Use concepts learned from previous weeks to try and get as high a score as possible

[X] Evaluate the techniques that work the best and discuss why you think this is the case

The following advanced user stories are optional. You're not required to do these, but you will learn more from doing them:

### Optional
[] Use n-grams in the Bag of Words and TF-IDF representations by setting ngram_range in CountVectorizer and TfidfVectorizer. (You can learn about n-grams here).
[] Try filtering out lyrics that are not in English.
[] Explore Doc2VecHelperFunctions.ipynb, and try to choose different parameters for model_vector_size, model_epoch_range etc. and see how it affects your model or if you can get a better score. You can try using GridSearchCV to do this. (Remember that training the Doc2Vec model takes a lot of time!)
[] Try using KMeans Clustering to plot your data from CountVectorizer/TfidfVectorizer/Doc2Vec and see if you can find any interesting clusters (Note This one is difficult! But here is a hint: you will first need to reduce the number of dimensions in your data using a technique like Principal Component Analysis - PCA in Python).

## Video Walkthrough

Here's a walkthrough:

![Video Walkthrough](walkthrough.gif)
