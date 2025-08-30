# Customer Sentiment Analysis & Topic Modelling

Analyze and extract actionable insights from 22,000+ women’s clothing e-commerce reviews using NLP and machine learning.

## Project Overview

This project demonstrates a full pipeline for:
- **Sentiment Analysis:** Classify reviews as positive, neutral, or negative using VADER and Logistic Regression.
- **Topic Modelling:** Discover key themes in customer feedback with Non-Negative Matrix Factorization (NMF).
- **Data Preprocessing:** Clean and normalize text, engineer features, and handle domain-specific language.

## Key Features

- **VADER Sentiment Analysis:** Fast rule-based sentiment scoring for raw reviews.
- **Logistic Regression:** TF-IDF vectorization and supervised sentiment classification.
- **Topic Modelling:** NMF extracts top keywords and representative reviews for each topic.
- **Hyperparameter Tuning:** Optuna + MLflow for automated model optimization.
- **Visualizations:** Confusion matrix, topic keyword charts, and sample outputs.

## Tech Stack

- Python, pandas, scikit-learn, NLTK, VADER, Optuna, MLflow, matplotlib, seaborn

## Usage

1. **Pre-Processing:** Run `Pre-Processing.ipynb` to clean and prepare the dataset.
2. **EDA:** Explore data in `EDA.ipynb`.
3. **Modelling:** Train and evaluate models in `Modelling.ipynb`.

## Dataset

- [Womens Clothing E-Commerce Reviews (Kaggle)](https://www.kaggle.com/datasets/nicapotato/womens-ecommerce-clothing-reviews)

## Results

- Achieved >80% accuracy in sentiment classification.
- Extracted granular topics (fit, style, material, etc.) from reviews.

## Folder Structure
