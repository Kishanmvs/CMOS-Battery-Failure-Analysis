# CMOS Battery Predictive Failure Analysis

A machine learning project for predicting CMOS battery failure using system telemetry data.

## Overview

The project analyzes system-level signals such as battery voltage, RTC drift, boot errors, system age, power cycles, and temperature to identify systems at risk of CMOS battery failure.

## Features

- Exploratory Data Analysis
- Feature Engineering
- Machine Learning Model Training
- Failure Prediction
- Model Evaluation using Recall and ROC-AUC

## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Dataset

The dataset contains 5,000 system telemetry records with 10 features related to CMOS battery health and system behavior. :contentReference[oaicite:0]{index=0}

## Model

The project experiments with Logistic Regression and Random Forest models. Feature engineering is used to capture relationships between voltage, temperature, system age, RTC drift, and other telemetry signals. :contentReference[oaicite:1]{index=1}

## Evaluation

The main focus is on **Recall for the failure class** and **ROC-AUC**, since missing a potential battery failure is more important than overall accuracy. :contentReference[oaicite:2]{index=2}
