# Movie-Recommender-using-Python

This repository contains a Python implementation of a movie recommender system. The code reads in a dataset of user ratings for movies and performs 
various analyses to generate movie recommendations based on user preferences.

# Getting Started
## Prerequisites
Before running the code, make sure you have the following libraries installed:

NumPy
Pandas
Matplotlib
Seaborn

# Installation

You can install the required libraries using pip:

Copy code/-
pip install numpy pandas matplotlib seaborn

#Usage
To use the code, simply run the Jupyter notebook file- Recommender Systems with Python.ipynb
The notebook contains the following sections:

1. Data loading and cleaning: Reads in the movie ratings data and cleans it up by merging it with a dataset of movie titles.
2. Exploratory data analysis: Performs basic exploratory data analysis on the ratings data, including calculating summary statistics and
   creating histograms and scatterplots to visualize the distribution of the data.
3. Movie correlation analysis: Uses the ratings data to compute the correlation between the ratings of each movie and the ratings of
   two specific movies, 'Star Wars (1977)' and 'Liar Liar (1997)'. Outputs a DataFrame of the top 10 movies that
   are most highly correlated with each of these two movies, filtered to only include movies with more than 100 ratings.
    
# Contributing
Contributions are welcome! If you find a bug or have a suggestion for how to improve the code, please open an issue or submit a pull request.

License
This project is licensed under the MIT License - see the LICENSE file for details.
