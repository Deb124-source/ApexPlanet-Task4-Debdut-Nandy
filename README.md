
# Advanced Analytics on Online Retail Data

## ApexPlanet Data Analytics Internship — Task 4

This project applies statistical analysis, customer
segmentation and predictive modeling to an Online
Retail dataset.

## Project Objectives

- Analyze transaction-level sales statistics.
- Perform hypothesis testing and confidence interval estimation.
- Segment customers using RFM and K-Means clustering.
- Visualize customer segments using PCA.
- Predict daily revenue using Linear Regression.

## Technologies

Python, Pandas, NumPy, SciPy, Matplotlib, Seaborn,
Scikit-learn and Google Colab.

## Statistical Analysis

Descriptive statistics, a 95% confidence interval,
Welch's t-test and a chi-square test were performed.

## Customer Segmentation

RFM analysis was used to create customer-level
features. K-Means clustering identified customer
groups based on purchasing behavior.

The elbow method and silhouette scores were used
to evaluate the cluster count, and PCA was used
for visualization.


## Predictive Modeling

A Linear Regression model was trained to predict
daily revenue using historical revenue features.

### Model Performance

| Metric | Result    |
|--------|----------:|
| MAE    | £6,333.93 |
| RMSE   |  £7,868.82|
| R²     | 0.5060    |

The model was evaluated using a chronological
training and testing split.


## Dataset

UCI Machine Learning Repository — Online Retail

https://archive.ics.uci.edu/dataset/352/online+retail

The cleaned dataset was prepared during Task 1
of the internship.

## Project Limitations

The dataset covers approximately one year.
The forecasting model is intended for educational
analysis rather than production deployment.
