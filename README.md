# Spotify Song Analysis & Popularity Prediction

![Project Banner]

## 🎵 Project Overview

This project analyzes a dataset of over 114,000 songs from Spotify to uncover the key audio features that drive popularity. The analysis includes a full data science workflow: data cleaning, exploratory data analysis (EDA), predictive modeling, and unsupervised clustering. The ultimate goal is to understand the "sonic DNA" of a successful song and different music genres.

---

## 🛠️ Technologies Used

-   **Python:** Core programming language.
-   **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn.
-   **Jupyter Notebook:** For interactive analysis and visualization.

---

## 📊 Key Findings & Visualizations

### 1. What Makes a Song Popular?
Exploratory analysis revealed that **loudness and energy** are the strongest positive predictors of popularity. In contrast, **acousticness** has a strong negative correlation, suggesting that highly produced, non-acoustic tracks tend to be more popular.

### 2. Predictive Modeling
-   **Popularity Prediction:** A Random Forest Regressor model was built to predict a song's popularity, achieving an **R-squared of 0.53**.
-   **Genre Classification:** A Random Forest Classifier successfully categorized songs into their genres with **74% accuracy** based only on audio features.



### 4. Song Clusters
K-Means clustering identified 5 distinct groups of songs based on their sound, revealing natural groupings that exist beyond traditional genre labels.

![Song Clusters Chart]

---

## 🚀 How to Run this Project

1.  Clone this repository:
    ```bash
    git clone [https://github.com/YourUsername/spotify-music-analysis.git](https://github.com/YourUsername/spotify-music-analysis.git)
    ```
2.  Navigate to the project directory:
    ```bash
    cd spotify-music-analysis
    ```
3.  Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```
4.  Open the notebook in Jupyter:
    ```bash
    jupyter notebook notebooks/music_analysis.ipynb
    ```
