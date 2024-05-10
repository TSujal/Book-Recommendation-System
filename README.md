# Book-Recommendation-System
This repository contains a collaborative book recommendation system developed using data science techniques. The system utilizes collaborative filtering algorithms to recommend books based on the user preferences.

## Introduction
Welcome to the Book Recommender System project! This project implements a collaborative book recommendation system using data science techniques. The system provides personalized book recommendations based on user ratings and book attributes. It employs collaborative filtering algorithms to suggest books similar to those liked by the user.

## Features
- **Collaborative Filtering:** Utilizes collaborative filtering algorithms to recommend books based on user ratings and preferences.
- **Popularity-Based Recommendations:** Provides recommendations for popular books based on the number of ratings and average ratings.
- **Content-Based Filtering:** Analyzes book attributes to recommend similar books to those already liked by the user.
- **Data Exploration:** Allows exploration of the dataset including books, user ratings, and user information.

## About Data-set
In this following project we are downloading the data from kaggle, the link for the data is as follow: https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset/data

The dataset contains 3 CVS files:
1) **Books.csv** : The Dataset contains 8 columns `ISBN`,`Book-Title`,`Book-Author`,`Year-Of-Publication` , `Publisher`, `Image-Url-S`,`Image-Url-M`,`Image-Url-L`. <br>
As the name suggest the <br>
`ISBN`: the serial unique number <br>
`Book-Title`: The name of the book.<br>
`Book-Author`: The name of the Author.<br>
`Year-Of-Publication`: The year in which the book is been published.<br>
`Publisher`: The name of the publisher where the book got published.<br>
And then the image of the book at amazon in Small,Medium,Large format [which for this project is not that important].
2) **Ratings.csv** : the rating.csv contains 3 columns ie  `User-ID`,`ISBN`,`Book-Rating` <br>
which is cruisal when it comes to details about the users which user have rated the book at what rating based on which many things can be done and analyzed.  <br>  
3) **Users.csv**: The users.csv contains 3 columns `User-ID`,`Location`, `Age`.
the User-ID contais the ID of the users as the name suggest the location and age is the residency of the user and age of the users.


## Procedure
We will be simply using this 3 dataset and then with the help of this 3 dataset we will be creating our own dataset which will be useful for further purposes.
then we will be using a collaborative recommendation system, by using cosine similarity 

Then at the end for this particular project we built a function which is nothing but a function which uses this cosin similarity to match and feed out the similar type of movies 
also if sometimes if any user makes a typo in the name of the movie still the function will give us the near about correct name of the movie and then also give us the recommended movies related to that particular movies.

Even the half name or even a word about the movie typed from the users will give you the whole movie name and then the function will utilize cosine similarity to give us 10 recommended books.

That way the whole project is been concluded.
