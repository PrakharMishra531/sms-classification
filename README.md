# SMS Classification Using Multinomial Naive Bayes Model

![Python](https://img.shields.io/badge/Python-3.9-blue.svg)
![scikit-learn](https://img.shields.io/badge/scikit--learn-0.24.1-orange.svg)
![pandas](https://img.shields.io/badge/pandas-1.2.3-yellow.svg)
![seaborn](https://img.shields.io/badge/seaborn-0.11.1-blue.svg)
![matplotlib](https://img.shields.io/badge/matplotlib-3.3.4-red.svg)
![wordcloud](https://img.shields.io/badge/wordcloud-1.8.1-lightgrey.svg)
![nltk](https://img.shields.io/badge/nltk-3.5-green.svg)
![Streamlit](https://img.shields.io/badge/Streamlit-0.82.0-brightgreen.svg)

## Overview

This project is an SMS classification web application that uses the Multinomial Naive Bayes machine learning model, along with bag-of-words and vectorization techniques, to classify sms messages if they are spam or not. The app is built using Streamlit for the frontend and employs several models including Multinomial Naive Bayes, K-Nearest Neighbors, and more to achieve high accuracy and precision.


## Live Demo

Check out the live demo of the application [here](https://sms-classification.streamlit.app/).

## Tech Stack

The project utilizes the following technologies:

## Tech Stack

| Technology    | Logo                                                                                      |
| ------------- | ----------------------------------------------------------------------------------------- |
| **Python**    | <img src="https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg" height="50"> |
| **scikit-learn** | <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" height="50"> |
| **pandas**    | <img src="https://upload.wikimedia.org/wikipedia/commons/e/ed/Pandas_logo.svg" height="50"> |
| **seaborn**   | <img src="https://seaborn.pydata.org/_static/logo-wide-lightbg.svg" height="50">           |
| **matplotlib**| <img src="https://matplotlib.org/_static/images/logo2.svg" height="50">                    |
| **nltk**      | <img src="https://miro.medium.com/v2/resize:fit:750/format:webp/1*YM2HXc7f4v02pZBEO8h-qw.png" height="50">                                     |
| **Streamlit** | <img src="https://streamlit.io/images/brand/streamlit-mark-color.svg" height="50">         |



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
