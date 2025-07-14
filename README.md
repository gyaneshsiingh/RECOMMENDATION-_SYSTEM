# 🎯 Recommendation System using Collaborative Filtering (SVD)

This notebook builds a **collaborative filtering recommendation system** using **matrix factorization (SVD)** with the **Surprise library**. It uses the **MovieLens 100k dataset** to predict user-item ratings and recommend top movies.

## 🧰 Tools Used:
- `surprise` library (SVD, Dataset, Reader)
- `collections.defaultdict`
- `train_test_split`, `accuracy`, `rmse`, `mae`

## 📌 What’s Included:
- Dataset loading from Surprise
- Train/test split
- SVD model training and prediction
- Evaluation with RMSE, MAE
- Function to generate top-N recommendations for each user
