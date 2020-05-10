# Sptify-Recommendation-System-Design

 The size of the original csv file is 556.8 MB.
 
 This dataset contains 22 columns of variables in total, including different audio features of Spotify songs crawled from Spotify API.
 
 The 13 audio features include danceability, energy, key, loudness, mode, speechiness, acousticness, instrumentalness, liveness, valence, tempo, duration_ms, and time_signature. 
 
 The other song features include position, track_name, artist, streams, url, year, month, day, and region. 
 
 This would be an important variable for our feature engineering.

## GCP Platform for computer engine

## Pyspark for speedy modeling (20 partitions in each RDD)

## Model Building:
### Classification:
#### SVM; XGBoost(reg:log as weak learner); KNN
### Tunning:
#### Grid Search; Cross Validation on Kfold

### Cluster:
#### Kmeans

## Visualization
### Profile digging with seaborn package
##### Drake, Ariana Grande and DJ Snake are the winners in 2018.
