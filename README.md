# WIDS_25
# Assignment 1 – Introduction to Python & Data Analysis
## Objectives
- Understand Python syntax and control structures
- Perform basic numerical operations using NumPy
- Load and manipulate datasets using Pandas
- Gain familiarity with Jupyter / Google Colab environment
## Tools & Libraries Used
- Python
- NumPy
- Pandas
- Jupyter Notebook / Google Colab
## Key Learnings
- Data loading and inspection
- Basic data preprocessing
- Writing clean and readable Python code
  
# Assignment 2 – Exploratory Data Analysis & Supervised Learning (Spotify Dataset)
## Dataset
- File name: `dataset.csv`
- Contains audio features of songs such as:
  - danceability
  - energy
  - loudness
  - tempo
  - valence
## Objectives
- Perform exploratory data analysis on the dataset
- Handle missing values and apply feature scaling
- Visualize audio feature distributions and correlations
- Build and evaluate classification models
## Tools & Libraries Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
## Tasks Performed
- Dataset inspection and summary statistics
- Handling missing values
- Standardization of numerical features
- Data visualization (histograms, boxplots, scatter plots, heatmaps)
- Mood classification using Logistic Regression
- Bonus model using K-Nearest Neighbors (KNN)
## Files
- `Assignment2_Spotify_EDA.ipynb` – Complete solution notebook

## Question 4 of Assignment 2 - Audio Features & Mood Analysis

### Description
This section focuses on understanding how Spotify audio features relate to the mood of a song.

### Audio Features Explained
- **Danceability**: Measures how suitable a track is for dancing based on tempo, rhythm stability, and beat strength.
- **Energy**: Represents the intensity and activity level of a track.
- **Valence**: Indicates the musical positivity conveyed by a track.

### Mood Identification
Songs that are perceived as **happy or energetic** generally have:
- High valence
- High energy
- Moderate to high danceability

Lower valence and energy values are often associated with sad or calm music.

### Insight
Audio features provide a meaningful numerical representation of music mood and can be effectively used for classification tasks in machine learning.

