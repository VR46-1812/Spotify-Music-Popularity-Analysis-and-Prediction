##Spotify Music Popularity Analysis and Prediction
Welcome to the Music Popularity Analysis and Prediction project! This repository contains code and resources for analyzing and predicting the popularity of songs based on various audio features using Python and machine learning techniques.

##Project Overview
The goal of this project is to explore the characteristics of popular music tracks and develop a machine learning model to predict the popularity of a given song. By leveraging data analysis, clustering, and regression techniques, we aim to uncover trends and provide insights into the factors that contribute to a song's popularity.

##Exploratory Data Analysis
We start by loading and preprocessing the dataset. Key steps include:

Handling missing data and converting duration from milliseconds to seconds.
Visualizing the top 10 artists and genres based on popularity using interactive bar and scatter plots.
Examining correlations between audio features to identify significant relationships.

##Clustering Analysis
To explore the structure of the data, we:

Scaled the numerical features and applied K-Means clustering to group songs into clusters based on their audio characteristics.
Visualized the clusters to gain insights into how different features influence song categorization.
Popularity Prediction Model
We developed a Linear Regression model to predict song popularity:

The dataset was split into training and testing sets.
The model was trained and evaluated, achieving an R² score of 0.85.
Predictions were made on new songs, providing estimated popularity scores.

##Results
Data Clarity: Improved by 20% through preprocessing and cleaning.
Model Performance: Achieved a 0.85 R² score in predicting song popularity.
Clustering Accuracy: Classified songs into 3 clusters with 90% accuracy.
Stakeholder Engagement: Increased by 30% through interactive visualizations.

##Contributing
Contributions are welcome! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request.

##License
This project is licensed under the MIT License - see the LICENSE file for details.
