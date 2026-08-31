# Cognifyz Machine Learning Internship

This repository contains my Machine Learning internship work completed at Cognifyz Technologies.

## Internship Tasks

### Task 1 — Restaurant Rating Prediction
A machine learning regression approach is used to predict restaurant aggregate ratings based on restaurant, location, service, pricing, and popularity-related features.

Models evaluated:
- Linear Regression
- Decision Tree Regression
- Random Forest Regression

### Task 2 — Restaurant Recommendation System
A content-based restaurant recommendation system is developed using user preferences such as city, cuisine, price range, minimum rating, and online delivery.

Techniques used:
- TF-IDF
- Cosine Similarity
- Preference-based filtering
- Similarity and rating-based ranking

### Task 3 — Cuisine Classification
A multiclass machine learning approach is used to classify restaurants according to their primary cuisine.

Models evaluated:
- Logistic Regression
- Random Forest Classifier

The dataset is processed to handle rare cuisine classes and prevent target leakage.

### Task 4 — Location-Based Analysis
A geographical analysis is performed using restaurant latitude, longitude, city, locality, ratings, price range, and cuisines.

The analysis includes:
- Restaurant distribution by location
- City and locality analysis
- Rating analysis
- Price range analysis
- Cuisine distribution
- Interactive geographical visualizations

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Plotly
- Jupyter Notebook

## Project Structure

```text
Cognifyz-ML-Internship/
│
├── dataset/
│
├── notebooks/
│   ├── 01_EDA_Data_Cleaning.ipynb
│   ├── 02_Task1_Rating_Prediction.ipynb
│   ├── 03_Task2_Restaurant_Recommendation.ipynb
│   ├── 04_Task3_Cuisine_Classification.ipynb
│   └── 05_Task4_Location_Analysis.ipynb
│
├── outputs/
│   ├── figures/
│   └── results/
│
├── reports/
│
├── src/
│
├── README.md
├── requirements.txt
└── .gitignore