# Movie-Recommendation-System-Using-RStudio-for-Data-Science

# Movie Recommendation System Using RStudio for Data Science

**Date**: 06/07/2023 - 25/12/2023  
**Author**: A Hima Sankar

## Overview
Have you ever used an online streaming platform like Netflix, Amazon Prime, or Voot? These platforms recommend movies and TV shows based on your watching patterns through a Recommendation System. In this Machine Learning project, I guide you through building your own Movie Recommendation System using R.

## Project Description
The main objective is to create an Item-Based Collaborative Filtering Recommendation System. We leverage user ratings and item similarities to offer relevant and engaging movie recommendations, enhancing user experience on streaming platforms.

## Key Steps:
1. **Data Pre-processing**:
   - Converted `userId` and `movieId` to factors.
   - One-hot encoded the genres column.
   - Created a search matrix and converted it to a `realRatingMatrix`.

2. **Building the Model**:
   - Developed an Item-Based Collaborative Filtering model using the `recommenderlab` package.
   - Visualized item similarities using a heatmap.

3. **Making Recommendations**:
   - Predicted top 10 movie recommendations for a user based on the model.

## Skills Gained
- Data Pre-processing and Manipulation
- Collaborative Filtering Techniques
- Data Visualization
- Recommender System Development
- Proficiency in R and its packages (recommenderlab, ggplot2, data.table, reshape2)

## Usage
Run the `movie_recommendation_system.R` script to execute the entire process from data pre-processing to making movie recommendations.

## Summary
This project demonstrates the power of recommendation systems in providing personalized content suggestions. By leveraging user ratings and item similarities, we successfully built a model that offers relevant movie recommendations.

## Top 10 Movie Recommendations:
1. Heat (1995)
2. Casino (1995)
3. Sense and Sensibility (1995)
4. Mr. Holland's Opus (1995)
5. Taxi Driver (1976)
6. Dave (1993)
7. The Piano (1993)
8. Searching for Bobby Fischer (1993)
9. Blade Runner (1982)
10. The Silence of the Lambs (1991)

Enjoy building your own Movie Recommendation System!
