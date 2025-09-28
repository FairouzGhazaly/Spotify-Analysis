# Spotify Data Analysis

## Overview

This project analyzes a large dataset of Spotify tracks to uncover trends, patterns, and relationships between audio features and track popularity. By leveraging data analysis and visualization techniques, the project explores what makes songs popular and how different musical attributes contribute to listener preferences.

The analysis includes **data cleaning**, **exploratory data analysis (EDA)**, **visualization of audio features**, and **feature correlations** to provide insights into the characteristics of trending songs.

## Dataset Details

The dataset is publicly available here: [Spotify Tracks Dataset](https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset).

It contains information about **125 genres** of tracks along with audio features provided by Spotify’s API.

### Columns Included:

* **track_id:** Unique Spotify track ID
* **artists:** Artists who performed the track
* **album_name:** Album the track belongs to
* **track_name:** Name of the track
* **popularity:** Popularity score (0–100)
* **duration_ms:** Track length in milliseconds
* **explicit:** Whether the track contains explicit content
* **danceability, energy, loudness, speechiness, acousticness, instrumentalness, liveness, valence:** Audio features describing various qualities of the track
* **tempo:** Beats per minute (BPM)
* **key, mode, time_signature:** Musical properties
* **track_genre:** Genre of the track

## Project Highlights

### 1. Data Cleaning & Preprocessing

* Handled missing values, dropped duplicates, and removed invalid records (e.g., tracks with zero duration).
* Transformed columns to ensure consistency and usability.

### 2. Exploratory Data Analysis (EDA)

* Summarized dataset shape, structure, and statistical descriptions.
* Investigated distributions of popularity, duration, tempo, and other features.

### 3. Data Visualization

Created multiple visualizations using **Matplotlib** and **Seaborn**, including:

* Distribution of popularity, loudness, and track durations.
* Boxplots and violin plots comparing features across genres.
* Scatter plots showing relationships between features (e.g., energy vs loudness, valence vs danceability).
* Correlation heatmap of all numeric features.
* Pie charts for explicit content and major/minor mode proportions.

### 4. Feature Analysis

* Analyzed how danceability, acousticness, energy, tempo, valence, and loudness vary across genres.
* Investigated correlations between features and popularity.
* Identified genre-specific trends in speechiness, instrumentalness, and liveness.

## Key Insights

* **Popular Tracks:** Higher popularity is often associated with strong energy and loudness levels.
* **Genre Trends:** Genres differ significantly in features like tempo, acousticness, and danceability.
* **Explicit Content:** Explicit songs form a significant share of tracks but are not necessarily more popular.
* **Correlations:** Features like energy and loudness are highly correlated, while valence and danceability show a moderate positive relationship.
* **Musical Preferences:** Most tracks are in **major mode**, but both major and minor modes contribute to popular songs.

## Why This Matters

Understanding music trends through data can help:

* **Artists and producers** optimize track composition for listener engagement.
* **Streaming platforms** improve song recommendations.
* **Researchers** study how music preferences evolve over time.

## Jupyter Notebook

The full code, visualizations, and step-by-step analysis are available in the notebook included in this repository.
