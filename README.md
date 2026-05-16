# ML Projects — Supervised Learning

A collection of machine learning projects built from scratch using Python, scikit-learn, pandas, and matplotlib.

## Projects

### 1. Heart Disease Prediction
- **Type:** Classification
- **Dataset:** UCI Heart Disease (303 patients, 13 features)
- **Models:** Logistic Regression, Random Forest, KNN
- **Best Model:** Random Forest — 83.6% accuracy, only 1 false negative
- **Key insight:** cp (chest pain type) is the most important feature

### 2. Titanic Survival Prediction
- **Type:** Classification
- **Dataset:** Titanic passenger data (891 rows, 11 features after cleaning)
- **Models:** Logistic Regression, Random Forest, KNN
- **Best Model:** Random Forest — 81.6% accuracy
- **Key insight:** Sex and Pclass are strongest survival predictors

### 3. Box Office Revenue Prediction
- **Type:** Regression
- **Dataset:** TMDB Movies (4803 movies)
- **Models:** Linear Regression, Random Forest, KNN
- **Best Model:** Linear Regression — R² 0.7485
- **Key insight:** Budget and popularity are strongest revenue predictors

### 4. California Housing Price Prediction
- **Type:** Regression
- **Dataset:** California Housing (20,640 houses, 8 features)
- **Models:** Linear Regression, Random Forest, KNN
- **Best Model:** Random Forest — R² 0.8051
- **Key insight:** KNN fails on large datasets — R² drops to 0.146

## Skills Demonstrated
- Data cleaning — null filling, dropping useless columns
- Feature encoding — Label Encoding, One Hot Encoding
- Model training and comparison
- Evaluation metrics — Accuracy, Confusion Matrix, R², RMSE
- Data visualization with Matplotlib

## Tech Stack
- Python 3
- pandas, NumPy
- scikit-learn
- Matplotlib
- Jupyter Notebook

## Author
Saad Imran — Software Engineering Student, AI/ML Enthusiast
