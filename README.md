# Netflix Movie Analysis & Recommendation System

An end-to-end data science project analyzing a movie dataset and building a personalized movie recommendation system using machine learning.

## 📌 Overview

This project performs comprehensive exploratory data analysis (EDA) on a movie dataset containing 9,800+ entries and builds a content-based movie recommendation engine using **K-Nearest Neighbors (KNN)**.

## 🔍 Key Features

- **Exploratory Data Analysis**:
  - Genre distribution analysis
  - Vote average categorization (Popular, Average, Below Average, Not Popular)
  - Year-wise movie release trends
  - Identification of highest/lowest popularity movies
  - Handling of multi-genre entries (exploding into single genres)

- **Data Preprocessing**:
  - Date conversion and feature extraction
  - Handling missing values
  - Label Encoding for categorical variables

- **Machine Learning Model**:
  - **K-Nearest Neighbors (KNN)** for movie similarity
  - Cosine similarity metric
  - Features used: Genre (encoded), Popularity, Vote Average

## 🛠 Technologies Used

- **Python**
- **Pandas**, **NumPy** – Data manipulation
- **Matplotlib**, **Seaborn** – Data visualization
- **Scikit-learn** – LabelEncoder, NearestNeighbors
- **Jupyter Notebook**

## 📊 Dataset

The dataset contains movie information including:
- Title, Release Date
- Genre (multi-genre support)
- Popularity Score
- Vote Count, Vote Average

## 🚀 How It Works

1. **Preprocessing** – Clean data, handle genres, encode categorical features.
2. **Feature Engineering** – Select relevant features (Genre_encoded, Popularity, Vote_Avg_encoded).
3. **Model Training** – Fit a NearestNeighbors model with cosine similarity.
4. **Recommendation** – Input a movie name → system returns top 5 similar movies based on feature similarity.

Contact
For questions, feedback, or collaboration:

LinkedIn: www.linkedin.com/in/rahul-pal-81ab29272
Email: pal164087@gmail.com
Naruto: The Lost Story - Mission: Protect the Waterfall Village!
Crime Busters
