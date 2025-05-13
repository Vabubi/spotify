# Spotify Analysis

## Project Description

`spotify_analysis` is a simple EDA project using Python libraries such as NumPy, Pandas, Matplotlib and Seaborn to load, clean and explore the 2020 Top 50 global Spotify tracks. The aim of this project is to examine audio characteristics such as danceability, energy and loudness to identify the features that underpin a successful hit.

### Table of contents in the notebook:
1. Project Setup and Data Acquisition

2. Data Loading and Initial Exploration

    2.1 Data Loading & Initial Exploration

    2.2 Inspect DataFrame Summary

    2.3 Summary Statistics for Numeric Audio Features

3. Data Cleaning

    3.1 Check for Missing Values

    3.2 Duplicate Row Check

    3.3 Treating Outliers

4. Exploratory Data Analysis

    4.1 Basic Stats & Structure

    4.2 Artist & Album Checks

    4.3 Track-Level Queries

    4.4 Genre Breakdown

    4.5 Correlation Overview

    4.6 Genre Comparisons

5. Summary & Insights
---
### How to use:
1. Clone the repository

        git clone https://github.com/Vabubi/spotify.git
2. Enter the project folder

        cd spotify_project
3. Activate your environment

        jupyter notebook
   Then open `Notebooks/spotify_analysis.ipynb` to start analysis.
---
### Data:
- **Source file**: data/spotifytoptracks.csv
- **Records**: 50 tracks
- **Features**: 16 columns including:
  - 5 Categorical columns: artist, album, track_name, genre
  - 11 Numeric features: energy, danceability, loudness, acousticness, etc.
---
### File Structure:
- Spotify_project/ The root directory housing project folders and the main README.

      data/
      notebooks/
      .gitignore
      README.md
      requirements.txt
- data/ Contains the raw dataset file spotifytoptracks.csv with the top-50 tracks.

      spotifytoptracks.csv
- notebooks/ Holds the interactive analysis notebook (`Spotify_analysis.ipynb`), its checkpoint folder (`.ipynb_checkpoints`), and a PDF export (`Spotify_analysis.pdf`).

      .ipynb_checkpoints/
      Spotify_analysis.ipynb
      Spotify_analysis.pdf

* .gitignore

  Specifies files and folders to exclude from version control (caches, envs, checkpoints, IDE/OS junk, etc.).
* requirements.txt

  Lists the Python dependencies needed to run the project.
* README.md

  Provides the project overview, setup steps, and usage instructions.
---
### Prerequisites:

- Python 3.8 or higher
- pip (Python package installer)
- Git (to clone the repository)
- Jupyter Notebook or JupyterLab
- Project dependencies (install with `pip install -r requirements.txt`)
---
### Contributing
Contributions are welcome!
## Author
Created by Jokūbas
