# 🎬 Movie Recommendation System (Machine Learning Project)

## Overview

This project is a **Content-Based Movie Recommendation System** built using Machine Learning.  
It recommends movies based on similarity between movie features such as genres and titles.

The system works similarly to recommendation engines used in platforms like Netflix.

---

## How It Works

The system uses:

- TF-IDF Vectorization to convert movie features into numerical vectors
- Cosine Similarity to measure how similar two movies are

Mathematically, similarity is computed as:

cos(θ) = (A · B) / (||A|| ||B||)

---

## Dataset

We use the MovieLens dataset containing:

- movies.csv → movie titles and genres
- ratings.csv → user ratings (optional for future improvements)

---

## Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn

---

## Features

- Load and explore movie dataset
- Feature engineering using genres and titles
- Compute similarity between movies
- Recommend top 10 similar movies
- Simple and extendable ML pipeline

---

## How to Run

1. Clone the repository

```bash
git clone https://github.com/AbdurahmanGhannam/movie-recommender.git
```

2. Install dependencies:
   'pip install pandas numpy scikit-learn'

3. Open Jupyter Notebook
4. Run the notebook step by step

Example Output

Input:

Toy Story (1995)

Output:

Toy Story 2
A Bug's Life
Monsters Inc
Finding Nemo
Shrek

...



Author

Built by an aspiring AI Engineer focusing on:

Machine Learning
Recommendation Systems
Applied AI
