# Spotify Tracks Analysis

Analysis of music tracks from Spotify using Python and pandas.

## Project Description

This project contains an analysis of the Spotify Features dataset, including:
- Data preprocessing
- Handling missing values and duplicates
- Outlier analysis
- Feature engineering
- Exploratory data analysis

## Dataset

Uses the "Ultimate Spotify Tracks DB" dataset from Kaggle, containing 232,725 tracks with 18 audio features.

## Project Structure

- `spotify_analysis.ipynb` - Main Jupyter Notebook with analysis
- `README.md` - This file

## Features

- Data cleaning and preparation
- Duplicate track identification and removal
- Outlier detection and handling
- Creation of new features (dance_energy_index, mood_category, emotional_spectrum)
- Statistical analysis and insights

## Technologies

- Python 3
- Pandas
- NumPy
- Jupyter Notebook

## Installation & Setup

1. Install dependencies:
```bash
pip install pandas numpy jupyter kagglehub
```

2. Run Jupyter Notebook:
```bash
jupyter notebook
```

3. Open `spotify_analysis.ipynb`

## Key Steps

1. **Data Loading**: Download and load dataset from Kaggle
2. **Data Cleaning**: Handle missing values, duplicates, and inconsistencies
3. **Outlier Treatment**: Identify and handle outliers in numerical features
4. **Feature Engineering**: Create new meaningful features for analysis
5. **EDA**: Explore relationships between audio features and popularity

## Results

The analysis provides insights into:
- Audio characteristics across different genres
- Relationships between danceability, energy, and popularity
- Mood classification of tracks based on audio features
- Duration patterns across music genres

## License

This project is for educational purposes.

---

*Note: The dataset is sourced from Kaggle and subject to their terms of use.*
