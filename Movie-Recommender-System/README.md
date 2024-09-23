# Project Title: Recommender System for Movies

## Overview
This project develops a recommender system using the small MovieLens dataset. The system allows users to input a movie title and receive recommendations for ten other similar movies.

## Dataset Description
The dataset includes two files:
- `movies.csv`: Contains movie IDs and titles.
- `ratings.csv`: Contains user ratings for the movies.

- **Source**: MovieLens dataset

## Methodology
1. **Data Loading**: Loaded the movies and ratings datasets.
2. **Data Preprocessing**: Merged the datasets and created a user-item matrix.
3. **Similarity Calculation**: Calculated cosine similarity between the movies based on user ratings.
4. **Recommender System**: Developed a function to recommend ten movies similar to a given movie.

## Key Findings
The recommender system was able to suggest similar movies based on user preferences, with high accuracy for popular movies.

## Tools & Technologies Used
- Python (Jupyter Notebooks)
- Libraries: pandas, scikit-learn, numpy

## Instructions for Use
1. Clone the repository.
2. Run the Jupyter Notebooks under the `Movie Recommender System` folder.
