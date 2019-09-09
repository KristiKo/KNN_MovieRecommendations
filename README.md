# KNN_MovieRecommendations
People who watched also watched

This project creates something similar to 'people who watched ... also watched'

We'll try to guess the rating of a movie by looking at the 10 movies that are closest to it in terms of genres and popularity.
We are using K Nearest Neighbours to define distance metric between the items in the dataset, and find the K closest items.
After we use those items to predict some property of a test item, by having them somehow "vote" on it.
