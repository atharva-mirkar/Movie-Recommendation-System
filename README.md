# Movie Recommendation System

This repository contains code for a movie recommendation system based on content filtering. The system utilizes data from the [TMDB 5000 Movie Dataset](https://www.kaggle.com/tmdb/tmdb-movie-metadata) and is implemented in a Jupyter Notebook.

## Project Overview

The project involves the following key steps:

1. **Data Loading and Exploration:**
   - Two datasets (`tmdb_5000_movies.csv` and `tmdb_5000_credits.csv`) are loaded to gather information about movies and their credits.
   - Initial exploration of the datasets, checking shapes, and displaying sample data.

2. **Data Cleaning and Preprocessing:**
   - Unnecessary columns are removed to focus on relevant features.
   - Various functions (`extract`, `extract_cast`, `extract_crew`) are defined to extract information from JSON-like strings.
   - Feature engineering is performed to create meaningful tags for movies.

3. **Data Visualization:**
   - A histogram of the 'vote_average' column is plotted using Seaborn.

4. **Text Vectorization:**
   - The movie tags are vectorized using TF-IDF (Term Frequency-Inverse Document Frequency).

5. **Cosine Similarity:**
   - Cosine similarity is calculated based on the TF-IDF vectors.

6. **Movie Recommendation:**
   - A recommendation function is implemented to suggest movies similar to a given title.

## Acknowledgements
   - The dataset used in this project is sourced from TMDB(https://www.themoviedb.org/).
