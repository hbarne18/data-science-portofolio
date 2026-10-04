# Predicting Higher Perceived Stress Using Lifestyle and Behavioral Factors

## Project Overview

This machine learning project examines whether lifestyle and behavioral
characteristics can be used to predict higher perceived stress among college
students.

The project uses survey data from the Dryad Digital Repository and focuses on
five predictors:

- Sleep duration
- Sleep quality
- Vigorous physical activity
- Caffeine use
- In-person social interaction

Two classification models were developed and compared: logistic regression
and a decision tree classifier.

## Results

Logistic regression was the better-performing model, achieving approximately
55.6% accuracy and 75.2% recall. The results suggest that the selected
lifestyle and behavioral variables contain some information related to
perceived stress, but they are not sufficient for highly accurate prediction.

## Files

- `mental-health-stress-prediction.ipynb` — Complete Jupyter Notebook containing
  data preparation, exploration, modeling, evaluation, and interpretation.

## Data Source

Data for this project was obtained from the Dryad Digital Repository:

https://doi.org/10.5061/dryad.zgmsbcct8

## Tools

Python, pandas, NumPy, Matplotlib, Seaborn, and scikit-learn.
