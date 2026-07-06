#  Rain Prediction using Random Forest

##  Project Overview

This project builds a machine learning model to predict whether it will rain tomorrow based on historical weather observations. Several preprocessing techniques were applied before training a Random Forest classifier. The model was then compared with a Logistic Regression classifier.

---

##  Dataset

The dataset contains daily weather observations with features such as:

- Temperature
- Humidity
- Rainfall
- Wind Speed
- Wind Direction
- Atmospheric Pressure
- Cloud Cover
- Sunshine
- Evaporation
- Rain Yesterday

**Target variable:**

- `RainTomorrow`
  - Yes
  - No

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

##  Data Preprocessing

The preprocessing pipeline includes:

- Handling missing values
- One-Hot Encoding for categorical variables
- Standard Scaling for numerical variables
- ColumnTransformer
- Pipeline

---

##  Models

### Random Forest Classifier

Hyperparameters were optimized using GridSearchCV.

Example parameters:

- n_estimators
- max_depth
- min_samples_split

### Logistic Regression

The Random Forest model was compared with Logistic Regression using:

- Solver: liblinear
- Penalty: L1 / L2
- Class Weight: None / Balanced

---

##  Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- Classification Report

---

##  Feature Importance

The Random Forest model provides feature importance scores to identify which variables contribute the most to predicting rain.

Some of the most important features include:

- Humidity3pm
- Rainfall
- Pressure3pm
- Sunshine
- Cloud3pm

---

##  Results

The Random Forest classifier achieved better overall performance than Logistic Regression by:

- Higher prediction accuracy
- Better recall for rainy days
- Improved handling of non-linear relationships
- More robust predictions

---

##  Skills Demonstrated

- Data Cleaning
- Feature Engineering
- Machine Learning Pipelines
- Hyperparameter Tuning
- Random Forest
- Logistic Regression
- Model Evaluation
- Data Visualization

---

##  Author

Feryel Hmaidi
