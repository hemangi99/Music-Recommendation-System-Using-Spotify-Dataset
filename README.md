<h1 align="left"> Music Recommendation System using Spotify Dataset <img src="https://upload.wikimedia.org/wikipedia/commons/8/84/Spotify_icon.svg" alt="spotify_logo" width="40" height="38"/> </h1>

## Overview
This project involves the development of a Music Recommendation System using the Spotify Dataset. The process includes exploratory data analysis (EDA) with visualization techniques to understand the dataset's characteristics and select relevant features for building an effective recommendation system.

## Data Loading <img src="https://static.vecteezy.com/system/resources/previews/025/781/125/non_2x/loading-icon-isolated-on-white-background-download-sign-load-icon-data-loading-bar-vector.jpg" alt="data_loading" width="25" height="25"/></h3>
The dataset is loaded from CSV files, including data on songs, genres, and yearly information.


## Exploratory Data Analysis <img src="https://static.vecteezy.com/system/resources/previews/024/193/986/non_2x/green-and-white-searching-data-analysis-in-computer-icon-vector.jpg" alt="data_analysis" width="27" height="27"/></h3>

<h4>Music Over Time</h4>
Data is grouped by year to observe the evolution of music characteristics from 1921 to 2020.

<h4>Characteristics of Different Genres</h4>
Audio features of different genres are compared to identify distinctive sound characteristics.

<h4>Feature Correlation Analysis</h4>
Feature correlation analysis is conducted to understand relationships between audio features and the popularity of songs.


## Building Recommender System</h3>

- Leveraging insights from clustering, a recommendation system is implemented using Spotipy, a Python client for the Spotify Web API.


- Users can input songs they have listened to, and the system recommends songs with similar characteristics.

- Spotipy is used to fetch data and query Spotify's catalog for songs.

<h3>Clustering Genres with K-Means</h3>
K-means clustering is applied to categorize genres into clusters based on numerical audio features.

**Visualizing the Clusters with t-SNE <img src="https://img.freepik.com/premium-vector/minimalistic-vector-illustration-growth-chart-upwards-personal-achievements-success_647003-190.jpg" alt="data_analysis" width="27" height="27"/>**

t-SNE is used to visualize genre clusters in a two-dimensional space.

<h3>Clustering Songs with K-Means</h3>
K-means clustering is applied to categorize songs into clusters based on numerical audio features.

**Visualizing the Clusters with PCA <img src="https://img.freepik.com/premium-vector/minimalistic-vector-illustration-growth-chart-upwards-personal-achievements-success_647003-190.jpg" alt="data_analysis" width="27" height="27"/>**

PCA is used to visualize song clusters in a two-dimensional space.


<h3>Installation</h3>

```pip install pandas seaborn plotly scikit-learn yellowbrick spotipy```

<h3>Usage</h3>

- Load the dataset using the provided code.

- Explore the data through visualizations and analyses.

- Apply clustering algorithms to genres and songs.

- Build and utilize the recommendation system.
