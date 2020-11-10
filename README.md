# Song-Genre-Classification-from-Audio-Data-using-ML
- Over the past few years, streaming services with huge catalogs have become the primary means through which most people listen to their favorite music. But at the same time, the sheer amount of music on offer can mean users might be a bit overwhelmed when trying to look for newer music that suits their tastes.
- For this reason, streaming services have looked into means of categorizing music to allow for personalized recommendations. One method involves direct analysis of the raw audio information in a given song, scoring the raw data on a variety of metrics.     
- In this project we will classify songs as being either 'Hip-Hop' or 'Rock' - all without listening to a single one ourselves.

# Dataset Description
- We have the metadata about our tracks alongside the track metrics compiled by The Echo Nest.
- The dataset has downloaded from https://www.kaggle.com/aniruddhachoudhury/classify-song-genres-from-audio-data
- A song is about more than its title, artist, and number of listens. We have another dataset that has musical features of each track such as danceability and cousticness on a scale from -1 to 1.
- These exist in two different files, which are in different formats - CSV and JSON. While CSV is a popular file format for denoting tabular data, JSON is another common file format in which databases often return the results of a given query.

# Approach for Problem Solving
1. Understanding the Problem
2. Downloading the Dataset
3. Importing necessary Dependencies
4. Univariate and Bivariate Analysis
5. Data Pre-processing
6. PCA
7. Building the Model
8. Evaluation of the Model
9. End Results

# End Results
- After all the possible experiments Maximum accuracy of 98.86% is achieved by using SVM and by making data balanced as Up Sampling.
- So, SVMs would accurately classify the Genre of the Songs if audio features have given.
- Surprisingly XGB Classifier does not give the accuracy better than SVM.



