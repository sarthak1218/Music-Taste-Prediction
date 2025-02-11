# Music Taste Prediction: Spotify Dataset

**Overview**

This project predicts a Spotify user's music preferences using machine learning models. Logistic Regression and K-Nearest Neighbors (KNN) are applied to forecast whether a user will like a particular song based on features such as danceability, energy, loudness, and tempo. The dataset is sourced from Spotify, and the project uses exploratory data analysis (EDA), feature scaling, and model evaluation to achieve accurate predictions.

**Methods Used:**

Logistic Regression: A linear model that predicts whether a user will like a song based on a threshold applied to the predicted probability.
K-Nearest Neighbors (KNN): A non-parametric model that uses the majority class of the nearest neighbors to predict user preferences.

**Features:**

1. Data Collection: Utilized the Spotify Dataset including audio features such as tempo, danceability, energy, and acousticness.
2. Data Preprocessing: Performed data cleaning, normalization, and feature scaling to prepare for analysis.
3. Exploratory Data Analysis (EDA): Visualized data distributions and feature relationships impacting user preferences.
4. Model Development: Implemented Logistic Regression and KNN to classify user preferences for songs.
5. Model Evaluation: Assessed model performance using metrics like accuracy, precision, recall, and confusion matrix.

**Technologies Used:**

Python
Pandas, NumPy
Scikit-learn
Matplotlib, Seaborn

**Results**

The performance of two machine learning models, Logistic Regression and K-Nearest Neighbours (KNN). This code evaluates the model using various metrics to assess its performance. An evaluation of the KNN model is conducted in a similar manner. Ultimately, a comparison is made betwen the F1-scores of both models to determine their relative performance. The evaluation function compiles important metrics to comprehensively assess the performance of each model and presents the results for convenient comparison.

*Metrics for Logistic Regression:*
Accuracy: 0.8974
Precision: 0.9000
Recall: 0.9000
F1 Score: 0.9000


*Metrics for Logistic Regression using Scikit:*
Accuracy: 0.9231
Precision: 0.9048
Recall: 0.9500
F1 Score: 0.9268


*Metrics for K-Nearest Neighbors (KNN):*
Accuracy: 0.8462
Precision: 0.8500
Recall: 0.8500
F1 Score: 0.8500

