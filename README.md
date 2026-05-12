# AI-Based Movie Recommendation System

## Project Overview
This project is a Machine Learning-based Movie Recommendation System developed using Python and Scikit-learn. The system recommends similar movies based on content similarity using TF-IDF Vectorization and Cosine Similarity techniques.

The recommendation engine analyzes movie titles and genres to generate personalized movie suggestions. This project demonstrates core Machine Learning concepts such as feature engineering, text vectorization, similarity modeling, and recommendation systems.

---

## Problem Statement
Online streaming platforms generate massive amounts of content, making it difficult for users to discover relevant movies. Recommendation systems help improve user experience by suggesting movies aligned with user interests and preferences.

This project builds a content-based recommendation system that identifies similar movies using textual features.

---

## Objectives
- Perform Exploratory Data Analysis (EDA) on movie datasets
- Apply feature engineering techniques
- Convert textual movie data into numerical vectors using TF-IDF
- Calculate movie similarity using Cosine Similarity
- Build an AI-powered recommendation engine
- Generate personalized movie recommendations

---

## Dataset Information
Dataset Used: MovieLens Dataset

Files Used:
- movies.csv
- ratings.csv

Dataset contains:
- Movie titles
- Genres
- User ratings
- Movie IDs

---

## Technologies Used

### Programming Language
- Python

### Libraries & Frameworks
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Machine Learning Concepts Used
- Recommendation Systems
- Content-Based Filtering
- Feature Engineering
- Text Vectorization
- TF-IDF (Term Frequency–Inverse Document Frequency)
- Cosine Similarity
- Similarity Modeling

---

## Project Workflow

### 1. Data Collection
Loaded movie and rating datasets using Pandas.

### 2. Exploratory Data Analysis (EDA)
<img width="991" height="611" alt="Screenshot 2026-05-12 213658" src="https://github.com/user-attachments/assets/54e061ab-fcb2-47e3-8492-40f0d64add16" />

Performed data understanding and visualization to analyze:
- Movie genres
- Data distribution
- Missing values

### 3. Feature Engineering
Combined movie titles and genres into a single feature column to improve recommendation quality.

### 4. Text Vectorization
Applied TF-IDF Vectorization to convert textual movie information into numerical feature vectors.

### 5. Similarity Calculation
Used Cosine Similarity to calculate similarity scores between movies.

### 6. Recommendation Engine
Built a recommendation function that returns the most similar movies based on user input.

---

## Example Recommendation

### Input
```python
recommend_movies('Toy Story (1995)')
```

### Output
- Toy Story 2
- Bug's Life
- Monsters Inc.
- Aladdin
- Lion King

---

## Key Features
- AI-powered recommendation engine
- Personalized movie suggestions
- Content-based filtering
- Similarity scoring system
- Scalable recommendation logic

---

## Screenshots
### Exploratory Data Analysis
<img width="1126" height="831" alt="Screenshot 2026-05-12 213818" src="https://github.com/user-attachments/assets/09baaaec-beb5-4afe-8238-e0a589e9b866" />


### Recommendation Output
<img width="555" height="772" alt="Screenshot 2026-05-12 213953" src="https://github.com/user-attachments/assets/3714fb5f-8c4c-46e9-993d-db3a91e49521" />


---

## Future Improvements
- Collaborative Filtering
- Hybrid Recommendation System
- User-Based Recommendations
- Streamlit Web Application
- Real-Time Recommendation API
- Deep Learning-Based Recommendation System

---

## Learning Outcomes
Through this project, I gained hands-on experience in:
- Machine Learning workflows
- Recommendation system development
- Feature engineering
- Text preprocessing
- Similarity-based modeling
- Data visualization and analysis

---

## Conclusion
This project demonstrates how Machine Learning techniques can be applied to build intelligent recommendation systems. By leveraging TF-IDF Vectorization and Cosine Similarity, the system successfully recommends movies with similar content characteristics.

---

## Author
Kirti Ramesh Gangarde

