# Compatibility_Project
Predicting romantic compatibility using machine learning and psychological profiles. XGBoost-based model built from speed dating and personality data.
# Finding the Perfect Match: A Machine Learning Approach to Romantic Compatibility

**Author:** Samuel Eubank  
**Program:** M.S. in Data Science and Analytics – College of Charleston

## Project Overview

Online dating platforms often rely on shallow matching algorithms that fail to capture deeper compatibility. This project leverages machine learning and psychological insights to predict romantic “matches” between participants based on personality, preferences, and behavioral data.

We combine multiple psychological and behavioral datasets and apply an XGBoost classification model to predict mutual interest in a speed dating scenario.

---

## Datasets Used

1. [Speed Dating Experiment Dataset (Kaggle)](https://www.kaggle.com/datasets/annavictoria/speed-dating-experiment)  
2. [OKCupid Profiles Dataset (Kaggle)](https://www.kaggle.com/datasets/andrewmvd/okcupid-profiles)  
3. [Big Five Personality Traits Dataset (Kaggle)](https://www.kaggle.com/datasets/tunguz/big-five-personality-test)

---

## Methods & Tools

- **Python**, **Jupyter Notebooks**
- **XGBoost Classifier** for prediction
- **SMOTE** for class imbalance
- **Principal Component Analysis (PCA)** for behavioral activity clustering
- **K-Means Clustering** for personality & dating preference grouping
- **Seaborn/Matplotlib** for visuals

---

## Feature Types

- **Demographic features**: Age, gender  
- **Personality & preference ratings** (self + date): Attractiveness, intelligence, fun, sincerity, ambition  
- **Behavioral clusters** from PCA (e.g., Activity Pattern 1, 2, 3)  
- **Psychological clusters** from Big Five & OKCupid data

---

##  Key Results

- **Accuracy**: ~84% on the test set  
- **F1 Score**: 0.51 (test), 0.85 (cross-validation)  
- **Top Predictors**: Attractiveness, fun ratings, shared interests, personality clusters, and activity patterns

See the full results and visualizations in the [poster](./images/poster_final.png)

Results are random but closely match the orignal above metrics.

---

##  How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/romantic-ml-matches.git
   cd romantic-ml-matches
