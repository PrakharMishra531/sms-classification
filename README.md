# Text Classification Web Application

![Python](https://img.shields.io/badge/Python-3.9-blue.svg)
![scikit-learn](https://img.shields.io/badge/scikit--learn-0.24.1-orange.svg)
![pandas](https://img.shields.io/badge/pandas-1.2.3-yellow.svg)
![seaborn](https://img.shields.io/badge/seaborn-0.11.1-blue.svg)
![matplotlib](https://img.shields.io/badge/matplotlib-3.3.4-red.svg)
![wordcloud](https://img.shields.io/badge/wordcloud-1.8.1-lightgrey.svg)
![nltk](https://img.shields.io/badge/nltk-3.5-green.svg)
![Streamlit](https://img.shields.io/badge/Streamlit-0.82.0-brightgreen.svg)

## Overview

This project is a text classification web application that uses Multinomial Naive Bayes machine learning model (and bag of words and vectorization) to classify text data. The app is built using Streamlit for the frontend and employs several models including Multinomial Naive Bayes, K-Nearest Neighbors, and more to achieve high accuracy and precision.

## Live Demo

Check out the live demo of the application [here](https://sms-classification.streamlit.app/).

## Tech Stack

The project utilizes the following technologies:

- **Python** ![Python](https://img.shields.io/badge/Python-3.9-blue.svg)
- **scikit-learn** ![scikit-learn](https://img.shields.io/badge/scikit--learn-0.24.1-orange.svg)
- **pandas** ![pandas](https://img.shields.io/badge/pandas-1.2.3-yellow.svg)
- **seaborn** ![seaborn](https://img.shields.io/badge/seaborn-0.11.1-blue.svg)
- **matplotlib** ![matplotlib](https://img.shields.io/badge/matplotlib-3.3.4-red.svg)
- **wordcloud** ![wordcloud](https://img.shields.io/badge/wordcloud-1.8.1-lightgrey.svg)
- **nltk** ![nltk](https://img.shields.io/badge/nltk-3.5-green.svg)
- **Streamlit** ![Streamlit](https://img.shields.io/badge/Streamlit-0.82.0-brightgreen.svg)

## Algorithms and Models

The following machine learning models were evaluated for text classification:

| Algorithm      | Accuracy | Precision |
| -------------- | -------- | --------- |
| K-Nearest Neighbors (KN) | 0.906190 | 1.000000 |
| Multinomial Naive Bayes (NB) | 0.974855 | 1.000000 |
| Extra Trees Classifier (ETC) | 0.976789 | 0.967213 |
| Support Vector Classifier (SVC) | 0.975822 | 0.966942 |
| Random Forest (RF) | 0.973888 | 0.966387 |
| Logistic Regression (LR) | 0.956480 | 0.951456 |
| XGBoost (xgb) | 0.967118 | 0.948276 |
| AdaBoost | 0.966151 | 0.947826 |
| Gradient Boosting Decision Trees (GBDT) | 0.952611 | 0.932039 |
| Bagging Classifier (BgC) |
