# League of Legends Diamond Ranked Games Prediction

A machine learning project for predicting the outcome of **League of Legends Diamond-ranked matches** using gameplay statistics from the first 10 minutes of a game.

This project was completed for the **Artificial Intelligence and Machine Learning course (CSE 3202)**. The dataset contains **9,879 matches and 40 original features**, sourced from Kaggle and based on Riot Games gameplay data.

## Project Overview

The analysis includes:

- Data preprocessing and feature cleaning
- Exploratory data analysis and correlation analysis
- Prediction of Blue team victory (`blueWins`)
- Comparison of multiple classification models
- Evaluation using accuracy, classification reports, and confusion matrices
- Comparison of 70/30 and 80/20 train-test splits

### Models

- Logistic Regression
- Gaussian Naive Bayes
- XGBoost
- Random Forest

## Results

Logistic Regression achieved the highest accuracy:

| Model | 70/30 Split | 80/20 Split |
|---|---:|---:|
| Logistic Regression | 72.17% | **73.28%** |
| Gaussian Naive Bayes | 72.10% | 71.71% |
| XGBoost | 70.68% | 70.55% |
| Random Forest | 72.23% | 72.22% |

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn
- XGBoost
- Jupyter Notebook

## Dataset

[Kaggle — League of Legends Diamond Ranked Games (10 min)](https://www.kaggle.com/datasets/bobbyscience/league-of-legends-diamond-ranked-games-10-min)

## Project Structure

```text
├── league.ipynb
├── high_diamond_ranked_10min.csv
└── README.md
```

## Authors

**Muhesena Nasiha Syeda**
&
**Souvik Ahmed**
