# Prediction of Host Professionalism in Barcelona's Airbnb Market

This R markdown file provides an analysis of the distribution of host professionalism in the Barcelona Airbnb market and a prediction of whether a listing is managed by single hosts or by corporations. This answers key questions about the dynamics of the local Airbnb market, such as the prevalence of professional hosts versus casual hosts, their geographic distribution, and factors influencing the likelihood of a listing being corporate-managed or single-host managed.

## Project Overview

This project employs EDA to analyze the target variable indicating host professionalism and its relationship with other variables through plots and statistical tests. After determining which variables are significant for the prediction of the target variable, different models are used (Logistic Regression, Naive Bayes CLassification and  k-Nearest Neighbor Algorithm) to predict whether a listing is managed by a single host or a corporation, as well as to identify the key factors driving these predictions.

## Findings

The kNN model achieved the best results, with an accuracy of about 80%. This suggests that the k-Nearest Neighbor algorithm is well-suited for predicting whether a listing is managed by a single host or a corporation based on the selected features.

## Requirements

The following R libraries are needed:

  - `naivebayes`
  - `ggplot2`
  - `psych`
  - `pROC`
  - `lubridate`
  - `Hmisc`
  - `dplyr`
  