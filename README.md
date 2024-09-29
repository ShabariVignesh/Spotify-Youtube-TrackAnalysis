# Spotify-Youtube-TrackAnalysis
This project explores how Spotify track audio features like energy, danceability, and tempo correlate with user engagement (likes, views, streams). It identifies high-engagement tracks needing promotion and compares performance between top artists on YouTube and Spotify.

### Key findings include:
- **Energy & Streams**: Tracks with high energy levels don't necessarily have more streams, showing a weak correlation.
- **Danceability & Likes**: Tracks that are more danceable tend to receive more likes.
- **High Engagement, Low Views**: Some tracks, despite having high engagement, are not widely viewed and could benefit from additional promotion.
- **Spotify vs YouTube**: In most cases, artists perform better on Spotify than on YouTube, with a few exceptions.

## Introduction
This project delves into how Spotify tracks' audio features, such as energy, danceability, tempo, and valence, influence user engagement metrics like likes, views, and streams. We aim to uncover patterns in user interaction, identify tracks with high engagement but low visibility, and compare platform performance for top artists (YouTube vs Spotify).

The analysis is structured around the following objectives:
- **Audio Feature Correlations**: Investigating how different track features correlate with engagement metrics.
- **Tracks Needing Promotion**: Identifying high-engagement tracks that have low view counts and may benefit from promotion.
- **Platform Performance**: Comparing streaming numbers for top artists on both YouTube and Spotify.

## Metadata
- **Dataset Source**: The dataset used in this project was downloaded from Kaggle (Spotify Dataset) and contains detailed information about Spotify tracks, including audio features and engagement metrics.
- **Files in the Project**:
  - `data/`: Contains the raw and cleaned data files used for the analysis.
  - `scripts/`: Contains Python scripts used to perform analysis and generate visualizations.
  - `sql_queries/`: SQL scripts for extracting and processing data.
  - `visualizations/`: Contains images of the plots and charts generated from the analysis.

## Tech Stack
- **SQL**: For querying and analyzing data from the dataset.
- **Python**: For further analysis, processing, and visualization (libraries used include Pandas, Matplotlib, and Seaborn).
- **GitHub**: For version control and project management.
- **Jupyter Notebook (optional)**: For exploring data and presenting visual analysis interactively.
