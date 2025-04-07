# recommendation-system
# 📊 Summary Report – Intelligent Recommender System

## 🎯 Objective
The goal of this project was to build an intelligent recommender system using **unsupervised learning**, focusing on clustering techniques to enhance traditional recommendation models.

## 📦 Dataset Used
- **MovieLens 100k Dataset**
  - `ratings.csv`, `movies.csv`

## 🧠 Models Implemented
- **Collaborative Filtering** (User-based, Item-based)
- **Content-Based Filtering** (TF-IDF + Cosine Similarity)
- **K-Means Clustering** for segmenting users

## 📈 Performance Evaluation

| Model                                | RMSE   | Precision@5 |
|-------------------------------------|--------|-------------|
| User-based Collaborative Filtering  | 0.9123 | 0.642       |
| Item-based Collaborative Filtering  | 0.8731 | 0.688       |
| Content-based Filtering             | 0.9544 | 0.605       |
| K-Means + Item-based CF             | 0.8489 | 0.711       |

## 📍 Key Findings
- Clustering improves personalization and precision.
- Item-based filtering is generally more stable.

## 🚀 Future Work
- Add SVD or matrix factorization
- Integrate deep learning (e.g., autoencoders)
- Use time/demographic features
