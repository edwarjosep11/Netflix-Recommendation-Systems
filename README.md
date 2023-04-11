# Movie Recommendation Systems
 
This project explores two different approaches to building movie recommendation systems: KNN Neighbors and Content-Based Collaborative Filtering. The goal is to predict which movies a user is likely to enjoy based on their previous ratings and preferences.

## Getting Started
To run this project, you'll need to have Python 3 installed, along with the following libraries:

* pandas
* numpy
* scikit-learn
* scipy
* matplotlib

Once you've installed these dependencies, you can open the Jupyter notebooks included in this repository:

* [KNN Neighbours approach.ipynb](./KNN%20Neighbours%20approach.ipynb)

* [ContentBased-CollaborativeFiltering.ipynb](./ContentBased-CollaborativeFiltering.ipynb)



Each notebook contains a different implementation of a movie recommendation system.

## KNN Neighbors
The KNN Neighbors notebook uses a K-Nearest Neighbors algorithm to find movies that are similar to a given movie, and recommends those similar movies to the user. The similarity between movies is based on the ratings given to each movie by users in the dataset.

## Content-Based Collaborative Filtering
The Content-Based Collaborative Filtering notebook uses a combination of user ratings and movie metadata (such as genre, director, and actors) to generate recommendations for a given user. This approach focuses on identifying patterns and similarities in the features of movies that a user has rated highly, and then recommending movies with similar features.

## Data
* The dataset used in this project is the MovieLens 100K dataset, which contains ratings for a set of 100,000 movies by a set of 943 users. The data can be downloaded from the [MovieLens website](https://grouplens.org/datasets/movielens/100k/).

* The dataset is based on TMDB movies dataset was also used, which is a record of about 5000 movies. You can find more information about this dataset on [Kaggle](https://www.kaggle.com/carolzhangdc/imdb-5000-movie-dataset).


## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
Thanks to the MovieLens team for providing the dataset used in this project, and to the developers of scikit-learn and other libraries used in this project for their contributions to the Python data science community.
