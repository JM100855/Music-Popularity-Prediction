The code files are not availabel at present but this documentations contains the code snippets and explanations of what was done. 
A small Overview is below:

# 🎵 Music Popularity Prediction

This project studies how song popularity relates to audio features and metadata from Spotify datasets. The aim is to understand which characteristics of a song are linked to popularity and to compare how different machine learning models perform on this task.

---

## Project Overview

Music platforms rank and recommend songs based on popularity. In this project, multiple Spotify datasets are analyzed and used to predict whether a song is popular based on measurable audio features. The work focuses on data preparation, analysis, and model comparison.

---

## Datasets Used

The project uses three Spotify-based datasets:

### Spotify Top 2000
- Audio features for 2,000 popular tracks released between 1956 and 2019
- Includes attributes such as BPM, energy, danceability, loudness, valence, and popularity score

### Top 50 Spotify Songs
- Audio features for the top 50 most streamed songs
- Used to compare results on a smaller dataset

### Large Song Dataset
- Around 19,000 songs with detailed audio features
- Includes tempo, key, acousticness, energy, speechiness, and popularity labels

---

## Data Preparation

- Checked for missing, duplicate, and inconsistent values
- Converted non-numeric values where needed
- Removed features not relevant to prediction
- Handled outliers
- Standardized numeric features for fair model comparison

---

## Data Analysis

- Summary statistics for all features
- Visualizations showing feature distributions
- Correlation analysis between audio features and popularity
- Plots to examine how attributes like energy, danceability, and loudness relate to popularity

---

## Models Used

The following models were trained and tested:

- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Support Vector Machine (SVM)  
- Decision Tree  

---

## Evaluation

- Train-test split on each dataset
- K-fold cross-validation
- Accuracy and F1-score comparison across models
- Statistical tests to compare model performance

---

## Results

- Logistic Regression worked well when feature relationships were mostly linear
- Decision Trees performed better on larger datasets with weaker correlations
- SVM produced stable results across datasets
- Audio features such as energy, loudness, and danceability showed clearer links to popularity

---

## Tools Used

- Python  
- NumPy  
- Pandas  
- Scikit-learn  
- Matplotlib  
- Seaborn  
- Plotly  

---

This project was completed as part of an academic course on data analysis and machine learning.

