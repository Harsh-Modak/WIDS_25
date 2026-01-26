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


# Assignment 3 – Unsupervised Learning & NLP (Spotify Dataset)

---

## Dataset

* File name: `dataset.csv`
* Contains Spotify audio features such as:

  * danceability
  * energy
  * loudness
  * tempo
  * valence

---

## Objectives

* Understand the concept of unsupervised learning
* Apply clustering techniques to real-world data
* Visualize high-dimensional data using PCA
* Learn probabilistic clustering using GMM
* Introduce basic Natural Language Processing (NLP) techniques

---

## Tools & Libraries Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* NLTK
* Google Colab / Jupyter Notebook

---

## Tasks Performed

### 1. Data Preparation

* Dataset loading and inspection
* Handling missing values
* Feature selection
* Feature scaling using StandardScaler

### 2. Hierarchical Clustering

* Agglomerative clustering using Ward linkage
* Dendrogram visualization (using a subset of data due to memory constraints)
* Cluster label assignment to the dataset

### 3. K-Means Clustering

* Elbow method for optimal K selection
* Final clustering using K-Means / MiniBatch K-Means
* Cluster label assignment

### 4. PCA Visualization

* Dimensionality reduction from 5D to 2D
* Visualization of clusters for:

  * K-Means
  * Hierarchical clustering

### 5. Gaussian Mixture Models (GMM)

* Probabilistic clustering using Gaussian distributions
* Soft cluster probability estimation

### 6. Bonus: Natural Language Processing (NLP)

* Tokenization
* Stemming
* Lemmatization
* Bag of Words (CountVectorizer)
* TF-IDF Vectorization

---

## Key Learnings

* Importance of feature scaling in distance-based algorithms
* Difference between hard and soft clustering
* Memory complexity of hierarchical clustering on large datasets
* Use of PCA for visualization of high-dimensional data
* Basics of converting text into numerical features

---

## Files

* `Assignment_3_wids_.ipynb` – Complete solution notebook for Assignment 3

---

## Notes

* Dendrograms were generated using a subset of 1000 samples to avoid RAM overflow in Google Colab (hierarchical clustering has O(n²) memory complexity).
* Full dataset was used for clustering algorithms (K-Means and GMM).

---

Submitted by: **Harsh Modak**
Institute: IIT Bombay

