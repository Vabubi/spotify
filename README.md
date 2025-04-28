# Spotify Analysis

#### Project Description

`spotify_analysis` is a Python project that retrieves and cleans data on the top 50 global Spotify tracks, then uses exploratory analysis and visualizations to uncover key audio-feature patterns, genre differences, and artist insights.

### Features

1. **Data Loading & Cleaning:** Import top-50 CSV, drop `Unnamed: 0`, remove missing/duplicate records.
2. **Descriptive Stats:** Compute summary stats for audio features; display schema/types.
3. **Outlier Detection:** Flag IQR outliers and output an outlier table.
4. **Exploratory Analysis:**
   - Artist/album hit counts
   - Top tracks by metric (e.g., danceability, loudness)
   - Genre distribution
   - Correlation heatmap
5. **Genre Comparison:** Contrast danceability, loudness, and acousticness across genres.
6. **Summary & Insights:** Summarize key findings and recommend next steps for curation and marketing.

---

# How to use

1. **Clone the repository**
   ```bash
   git clone https://github.com/Vabubi/spotify_analysis.git
   ```

2. **Enter the project folder**
   ```bash
   cd spotify_analysis
   ```

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```
   Then open `notebooks/spotify_analysis.ipynb` to start analysis.

---

## Data

- **Source file**: `data/spotifytoptracks.csv`
- **Records**: 50 tracks
- **Features**: 16 columns including:
  - `artist`, `album`, `track_name`, `genre`
  - `energy`, `danceability`, `loudness`, `acousticness`, etc.

---

## Project Structure:

· Spotify_project/

      data/
      notebooks/
      .gitignore
      README.md
      requirements.txt

· data/

      spotifytoptracks.csv

· notebooks/

      .ipynb_checkpoints/
      Spotify_analysis.ipynb
      Spotify_analysis.pdf

· Spotify_project

  The root directory housing project folders and the main README.

· data

  Contains the raw dataset file `spotifytoptracks.csv` with the top-50 tracks.

· notebooks

  Holds the interactive analysis notebook (`Spotify_analysis.ipynb`), its checkpoint folder (`.ipynb_checkpoints/`), and a PDF export (`Spotify_analysis.pdf`).

· .gitignore

  Specifies files and folders to exclude from version control (caches, envs, checkpoints, IDE/OS junk, etc.).

· requirements.txt

  Lists the Python dependencies needed to run the project.

· README.md

  Provides the project overview, setup steps, and usage instructions.

---

## Contributing

Contributions are welcome!

## Author

Created by Jokūbas.
