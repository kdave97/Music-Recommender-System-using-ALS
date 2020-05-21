# Music-Recommender-System-using-ALS

## Description
The project focuses on creating a music recommendation system that will suggest artists to user based on their listening history. The project uses collaborative filtering technique and uses Apache Spark and Python for implementation.

## Dataset
The dataset is a public song dataset from Audioscrobbler. This data set contains profiles for around 150,000 real people. The dataset lists the artists each person listens to, and a counter indicating how many times each user played each artist.
The files are present in the data_raw folder. A more detailed description about the dataset is given in the readme file of data_raw folder.

## Recommender Model
To get recommendations, following steps were performed:

* Perform Data Exploration to understand the dataset.
* Split the data into training, validation and testing set.
* Train the model using implicit feedback.
* Perform parameter sweep and choose the model that perform best on validation data.
* Predict the top 5 artists.


<b> Run the Music_recommender_ALS_Spark_Py.ipynb file 


