# Movie-Recommender-System

![](https://github.com/LasithaAmarasinghe/Movie-Recommendation-System/assets/106037441/67844ce1-e550-43c6-a98d-f0801243a1ea)

## Overview

- When a user enters a movie title into the input box, this recommendation system swiftly generates suggestions for other movies that may align with the user's preferences.
- This repository contains all the codes and resources used to build and utilize the recommendation system.

## Key Features

- **Data Exploration**: Comprehensive analysis to understand the MovieLens 25M dataset's structure and distribution.
- **Search Engine**: Building a search engine to find a specific movie title in the dataset. 
- **Recommendation Engine**: Creating a recommendation engine to suggest specific movies based on user preferences and movie ratings.

## Steps

* Reading in movie data with pandas.
* Cleaning movie titles with regex.
* Creating a [TF-IDF](https://www.geeksforgeeks.org/understanding-tf-idf-term-frequency-inverse-document-frequency/) matrix. (Time Frequency-Inverse Document Frequency)
* Creating a search function.
* Building an interactive search box with Jupyter.
* Reading in movie ratings data.
* Finding users who liked the same movie.
* Finding how much all users like movies.
* Creating a recommendation score.
* Building a recommendation function.
* Creating an interactive recommendation widget.


## Code

You can find the code for this project here:
- [Movie-Recommendation.ipynb](https://github.com/LasithaAmarasinghe/Movie-Recommendation/blob/main/Movie%20Recommendation.ipynb)
  
## Technologies/Tools 

* Jupyter Notebook / [Google Colab](https://colab.research.google.com/)
* Python 3.10.12
* Python packages
  * Pandas - `pip install pandas`
  * Numpy - `pip install numpy`
  * Scikit-learn - `pip install scikit-learn`
  * Regex - `pip install regex`

## Data

You can download the dataset files used in this project here:
* [MovieLens 25M dataset.](https://grouplens.org/datasets/movielens/25m/)
