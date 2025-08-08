# Netflix Recommendation System

A machine learning-powered **movie recommendation system** inspired by Netflix, built using collaborative filtering and matrix factorization techniques. This project predicts user preferences based on historical ratings to generate personalized movie recommendations.

---

## Features

- **Data Cleaning & Preprocessing**  
  Cleans the dataset, handles missing values, and selects relevant columns.

- **Exploratory Data Analysis (EDA)**  
  Visualizes user behavior and content trends using plots and correlation heatmaps.

- **Matrix Factorization (SVD)**  
  Applies Singular Value Decomposition to uncover latent user-item interactions.

- **Collaborative Filtering**  
  Recommends content based on user-user and item-item similarity.

- **Cosine Similarity Engine**  
  Computes similarity between movies for more accurate recommendations.

- **Evaluation Metrics**  
  Includes RMSE for performance evaluation and visual error analysis.

---

## Tech Stack

- **Python 3.x**
- **Pandas** & **NumPy**
- **Matplotlib** & **Seaborn**
- **Scikit-learn**
- **SciPy**

---

## Dataset


# Netflix Recommendation System

This project demonstrates a Netflix recommendation system using anonymized user ratings. The dataset (`netflixData.csv`) has been preprocessed to remove noise and irrelevant columns.

## How to Run

1. **Install dependencies**
  - Open a terminal in this folder.
  - Run:
    ```powershell
    pip install -r requirements.txt
    ```

2. **Run the notebook**
  - Open `Model.ipynb` in Jupyter Notebook or Colab.
  - Execute the cells step by step to train and test the recommender system.

## Files
- `Model.ipynb`: Main notebook containing code and explanations.
- `netflixData.csv`: Preprocessed dataset (add to folder if missing).
- `requirements.txt`: List of required Python packages.

## Future Improvements
- Integrate content-based filtering (using genres, cast, etc.)
- Hybrid recommender (combine collaborative + content-based)
- Web UI for real-time recommendations
---

## Future Improvements

- Integrate content-based filtering (using genres, cast, etc.)
- Hybrid recommender (combine collaborative + content-based)
- Web UI for real-time recommendations

---

## Inspiration

Inspired by the Netflix Prize challenge and modern recommender system research.


