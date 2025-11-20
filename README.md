# Wipro_Internship-Machine_Learning_with_Python
Machine Learning projects developed during my Data Science internship with Wipro (in collaboration with Elewayte/Acmegrade). Features a Breast Cancer Prediction Model and a Movie Recommendation System.


# Machine Learning Internship Projects 🤖

**Internship:** Wipro (in collaboration with Elewayte/Acmegrade)  
**Role:** Python & Machine Learning Intern  
**Duration:** 12 Nov 2024 - 12 Jan 2025  

This repository contains the source code, datasets, and documentation for the machine learning models I built during my industrial training and internship program.

## 📂 Project 1: Breast Cancer Prediction Model
A predictive model designed to classify breast cancer tumors as **Malignant** (cancerous) or **Benign** (non-cancerous) based on medical feature data.

* **Objective:** To assist in early diagnosis by automating tumor classification with high accuracy.
* **Algorithms Used:**
    * Logistic Regression
    * Support Vector Machine (SVM)
    * Random Forest Classifier
* **Key Steps:**
    * **Data Preprocessing:** Handled missing values and scaled features for better model performance.
    * **EDA:** Visualized correlations between tumor features using heatmaps and pair plots.
    * **Evaluation:** Achieved high accuracy and optimized for Recall to minimize false negatives.

## 📂 Project 2: Movie Recommendation System
A content-based recommendation engine that suggests movies to users based on similarity metrics.

* **Objective:** To solve the "cold start" problem in recommendation systems by suggesting items similar to what a user likes.
* **Technique:** **Cosine Similarity**.
* **Key Steps:**
    * **Feature Extraction:** Processed movie metadata (genres, keywords, cast, director).
    * **Vectorization:** Converted text data into numerical vectors using `CountVectorizer`.
    * **Similarity Calculation:** Computed the cosine distance between vectors to find the closest movie matches.

## 📂 Project 3: Music Recommendation System
A personalized recommendation engine designed to suggest songs based on user preferences and audio characteristics.

* **Objective:** To enhance user listening experience by clustering similar audio profiles.
* **Technique:** Collaborative Filtering / User-Preference Analysis.
* **Key Steps:**
    * **Data Analysis:** Analyzed user listening history and preference data.
    * **Feature Engineering:** Extracted and processed audio features to identify similarities between tracks.
    * **Modeling:** Built a recommendation logic to suggest new tracks that align with the user's taste profile.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Scikit-Learn, Pandas, NumPy, Matplotlib, Seaborn, NLTK
* **Tools:** Jupyter Notebook, VS Code
