# Movie Revenue Prediction Using Machine Learning Models

This project predicts movie revenue categories (Hit, Average, Flop) using machine learning models applied to metadata such as budget, genre, popularity, and release date. The goal is to compare different ML models and identify the best-performing approach for ROI-based prediction.

# Dataset
`train_movies.csv`
`validation_movies.csv`
`test_movies.csv`

# ROI Label Definition

We compute ROI as:

ROI = (revenue - budget) / budget

Then create a 3-class label:

- Hit: ROI ≥ 2.5567  
- Flop: ROI < 0.0049  
- Average: otherwise  

This method ensures a more realistic classification of movie financial performance.


# Methods & Models

 Classical Models
- Logistic Regression  
- Random Forest  
- KNN  
- SVM (RBF)  
- Gradient Boosting  

 Advanced Boosting Models
- Tang-style Optimized XGBoost (RandomizedSearchCV tuning)
- LightGBM (Novel model added to extend comparison)

 Ensemble Models
- Gupta-style Voting Ensemble
- Gupta-style Stacking Ensemble



