# Recommendations With IBM Project
This project was done as part of the requirements for Udacity Data Scientist Nanodegree

## Table of Content
1. Project Overview
2. Project Motivation
3. Project Tasks
4. Author, and Acknowledgement

## Project Overview
This project analyzes the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations about new articles that the users might like.

## Project Motivation
In order to determine which articles to show to each user, a study of the data available on the IBM Watson Studio platform was performed.

## Project Tasks
I. Exploratory Data Analysis: The first step is to explore the data.

II. Rank Based Recommendations: To get started in building recommendations, I started by finding the most popular articles based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles might be recommend to new users (or anyone depending on what is known about them).

III. User-User Based Collaborative Filtering: In order to build better recommendations for the users of IBM's platform, I focused on the users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users.

IV. Matrix Factorization: Finally, I completed a machine learning approach to building recommendations. Using the user-item interactions, I built out a matrix decomposition. Using this decomposition, i got an idea of how well i can predict new articles an individual might interact with.

## Author, and Acknowledgement
* Oluwatosin (Tosin) Obisan
* All credits to Udacity for providing the data set for this project.
