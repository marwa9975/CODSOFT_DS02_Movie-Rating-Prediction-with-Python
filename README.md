# Movie Rating Prediction with Python
<img src="data:image/png;base64,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" alt="image" width="700" height="300">


## Table of Contents
- [Project Overview](#Project-Overview)
- [Business Understanding](#Business-Understanding)
- [Objectives](##objectives)
- [Data Understanding](#data-understanding)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Modeling](#Modeling)
- [Recommendations](#recommendations)
- [Conclusion](#Conclusion)
- [Next Steps](#Next-Steps)

## Project Overview 
The Movie Rating Prediction project involves analyzing a dataset containing information about Indian movies. The dataset includes details like movie name, year, duration, genre, rating, votes, director, and three main actors. The data will be used to build a predictive model for movie ratings and extract valuable insights from the movie industry.
## Business Understanding
The film industry relies on understanding the factors that influence movie success. Accurately predicting movie ratings can aid in decision-making, such as choosing the right actors, directors, and genres, as well as determining marketing strategies
## Objectives
* Develop a predictive model: Create a machine learning model to predict movie ratings based on the provided dataset.This is essentially a regression problem, where we aim to estimate the numerical movie ratings based on various features.
* Identify influential factors: Analyze the dataset to determine which factors (e.g., genre, director, actors) have the most significant impact on movie ratings.
* Provide actionable insights: Offer insights to the film industry stakeholders to make informed decisions about movie production, casting, and marketing.
## Data Understanding
The dataset is obtained from Kaggle: [IMDb India Movies](https://www.kaggle.com/datasets/adrianmcmahon/imdb-india-movies)     

The dataset has the following columns:

``Name``: Movie name   
``Year``: release year of the movies   
``Duration``: Movie duration   
``Genre``: Movie genre    
``Rating``: Movie rating    
``Votes``: Number of votes received    
``Director``: Movie director   
``Actor 1``: First main actor    
``Actor 2``: Second main actor    
``Actor 3``: Third main actor   
## Exploratory Data Analysis
EDA inlude Rating analysis, Top 10 Directors with the Most Movies Directed, Top 10 Actors with the Most Movie Appearances, Top 10 Directors with the Highest-Rated Movies, Top 10 Highly Rated Movie Genres, Top 10 Years with Highest Average Ratings and Duration vs Rating
## Modeling
* Baseline Model - Linear Regression
* Second Model: Random Forest Model
* Third Model: Gradient Boosting Regressor
* Hyperparameter Tuning of Random Forest Model

The tuned Random Forest performed better than the tuned model in terms of model generalization and avoiding overfitting, due to its more balanced performance between training and test data. This will be the final model used for prediction.
### Most Important Features
Features that had the most significant impact on the target variable in the above model:
- Year
- Votes
- Duration
## Recommendations
- Year: Stay current with trends for successful movie releases.
- Votes: Encourage audience reviews for more reliable ratings.
- Duration: Align with audience preferences for movie length.
- Collaboration: Partner with established industry figures.
- Genres: Invest in highly-rated genres like History and Romance.
- Duration vs. Ratings: No strong duration-rating correlation.
- Critical Acclaim: Aim for positive reviews and acclaim
## Conclusion
In conclusion, this project provides valuable insights and a predictive model for movie rating prediction. The film industry can benefit from these findings to make data-driven decisions regarding movie production, casting, and marketing. The most influential factors identified are the year of release, the number of votes, and movie duration.
## Next Steps
- Model Refinement: Improve the rating prediction model with advanced machine learning methods.
- Feature Engineering: Enhance the model's performance by  experimenting with new features.
- User Reviews Analysis: Analyze user reviews and sentiments for deeper audience insights.
- Real-time Data: Implement real-time data updates to keep the model current with the latest trends

## Author
- Marwa Osman
- marwaosman9975@gmail.com
- [LinkedIn](https://www.linkedin.com/in/marwa-osman-00190b222/)
- [GitHub](https://github.com/marwa9975)

