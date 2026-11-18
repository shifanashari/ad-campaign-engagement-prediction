Ad Campaign Engagement Prediction

A Machine Learning project to predict advertisement campaign engagement using Python and multiple classification algorithms.

Project Overview

This project focuses on predicting whether users will engage with an advertisement campaign using machine learning techniques.

The project involves data preprocessing, exploratory data analysis, model training, evaluation, model comparison, and prediction.

Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook
* XGBoost

Machine Learning Models

The following nine classification algorithms were implemented and evaluated:

1. Logistic Regression
2. Decision Tree
3. K-Nearest Neighbors (KNN)
4. Support Vector Machine (SVM)
5. Naive Bayes
6. Gradient Boosting
7. AdaBoost
8. XGBoost
9. Random Forest

Project Workflow

* Data Preprocessing
* Exploratory Data Analysis (EDA)
* Model Training
* Model Evaluation
* Model Comparison
* Hyperparameter Tuning
* Prediction

Model Performance Results

The following table compares the original and tuned accuracy of nine machine learning classification models.

| Model | Original Accuracy (%) | Tuned Accuracy (%) |
|---|---:|---:|
| Decision Tree | 85.400 | 85.40 |
| AdaBoost | 85.325 | 85.30 |
| Gradient Boosting | 85.275 | 85.28 |
| XGBoost | 85.275 | 85.25 |
| SVM | 85.200 | 85.10 |
| Logistic Regression | 85.125 | 85.08 |
| Random Forest | 84.775 | 85.17 |
| Naive Bayes | 84.725 | 84.72 |
| KNN | 80.000 | 82.97 |

Key Findings

* Decision Tree achieved the highest accuracy of 85.40%.
* Random Forest improved from 84.775% to 85.17% after tuning.
* KNN improved from 80.00% to 82.97%.
* Decision Tree achieved the best overall accuracy among the evaluated models.

Exploratory Data Analysis – Correlation Analysis

A correlation matrix was used to understand the relationships between the numerical features and the target variable, Clicked on Ad.

Key Findings

* Daily Time Spent on Site showed the strongest positive correlation with ad clicks (0.73).
* Age showed a weak positive correlation (0.22).
* Area Income showed almost no linear correlation (0.01).
* Daily Internet Usage showed almost no linear correlation (0.00).
* Male showed almost no linear correlation (0.00).
* Clicks, Session Duration, and Previous Purchases also showed almost no linear correlation with the target variable.

Conclusion

Daily Time Spent on Site had the strongest linear relationship with the target variable among the listed features. However, correlation does not imply causation.

Project Files

* Advertisement Engagement Prediction.ipynb – Jupyter Notebook containing the complete project implementation.
* README.md – Project documentation.
