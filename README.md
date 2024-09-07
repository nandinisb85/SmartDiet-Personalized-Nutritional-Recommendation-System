# Nutritional Recommendation System

## Overview

The Nutritional Recommendation System is designed to provide personalized dietary suggestions based on users' nutritional goals. This system utilizes Python for data analysis and machine learning to recommend recipes that align with individual preferences.

## Steps

1. **Library Setup**
   - Loaded essential libraries including Pandas, NumPy, Scikit-learn, Matplotlib, and Seaborn for data processing and visualization.

2. **Data Loading & Exploration**
   - Utilized a comprehensive dataset of 7,806 recipes, examined its structure, addressed missing values, and removed irrelevant columns.

3. **Data Cleaning**
   - Handled missing values and standardized nutritional content (protein, carbs, fats) to ensure accurate clustering and recommendations.

4. **Data Splitting**
   - Divided the dataset into training and testing sets for model validation.

5. **Feature Engineering**
   - Encoded categorical variables such as Diet_type and Cuisine_type, and scaled numerical features (Protein, Carbs, Fats) for clustering and similarity calculations.

6. **Nutritional-Based Clustering**
   - Applied K-Means and Hierarchical Clustering algorithms to group recipes based on their nutritional profiles, enhancing recommendation accuracy.

7. **Diet Recommendation System**
   - Developed a cosine similarity-based recommendation system to suggest recipes that match users' dietary preferences and nutritional goals.

8. **Model Testing**
   - Evaluated the recommendation system using cross-validation and similarity scores.

## Dataset

The data used in this project is sourced from Kaggle's `All_Diets.csv`. This dataset provides detailed information on various recipes, including dietary types, cuisines, and nutritional content.

## Key Aspects

- **Programming Language**: Python for machine learning and data manipulation.
- **Data Exploration**: Visualized nutrient distributions across different diet types and cuisines.
- **Clustering**: Employed K-Means and Hierarchical Clustering techniques.
- **Recommendation System**: Implemented content-based filtering to provide personalized recipe recommendations.
- **Tools**: Pandas, Scikit-learn, Matplotlib, Seaborn for analysis and modeling.

## Future Scope

Future developments will focus on building both backend and frontend components to create a fully integrated application. This will enhance user interaction and make personalized nutritional recommendations more accessible.
