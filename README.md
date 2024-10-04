# Music Data Analysis: Logistic Regression & Clustering with Spotify API

## Project Overview
This project aims to analyze musical data from Spotify using logistic regression and clustering (k-means) techniques. It predicts the popularity of songs based on features like danceability, energy, valence, and tempo, and identifies patterns in song clusters using Spotify's music features data.

## Project Setup

### Requirements
To run this project, ensure you have the following:

- Python 3.8+
- Spotify API credentials (Client ID and Client Secret)
- Required libraries: `spotipy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`, `numpy`

### Installation

Clone the repository:


git clone https://github.com/username/music-analysis-spotify.git
cd music-analysis-spotify

## Project Features
- **Logistic Regression**: Predicts song popularity based on Spotify track features (danceability, energy, valence, etc.).
- **K-means Clustering**: Groups songs into clusters based on their features to identify patterns and musical styles.
- **Data Visualization**: Plots heatmaps, PCA, t-SNE, and clustering results to visualize relationships and clusters.

## Technologies Used
- **Spotify API**: Used to retrieve musical data from Spotify's music catalog.
- **Python**: Primary programming language.
- **Scikit-learn**: For machine learning models, logistic regression, and clustering.
- **Spotipy**: Python library for accessing Spotify's Web API.
- **Pandas**: Data manipulation and cleaning.
- **Matplotlib & Seaborn**: Data visualization libraries.

## Data Sources
The data used in this project is retrieved directly from **Spotify's Web API** using the `spotipy` Python client. Key features such as **danceability**, **energy**, **valence**, **tempo**, and **explicit** are extracted for analysis.
