# IMBD-movie-rating-prediction
Data Science project to predict IMDb movie ratings using machine learning.

## ✅ Task — IMDb Movie Rating Prediction

Dataset: Indian movies data from IMDb (`movies.csv`)
Goal: Predict the IMDb rating of a movie (scale 1–10)
Model Random Forest Regressor
MAE: 0.85
R² Score: 0.32

**What I did:**

- Explored and cleaned the dataset
- Handled missing values in Duration and Votes using median imputation
- Extracted numeric values from Duration and Year columns
- Applied log transformation on Votes to reduce skew
- Engineered new features: `movie_age` and binary genre flags for top 10 genres
- Split data into train/test sets (80/20)
- Built a Random Forest Regressor model
  - Evaluated using MAE and R² score
  - Plotted Actual vs Predicted ratings

**Key Finding:** Vote count (log-transformed) and movie age were the strongest predictors of IMDb rating
