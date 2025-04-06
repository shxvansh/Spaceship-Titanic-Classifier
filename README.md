# Spaceship-Titanic-Classifier

This repository contains a machine learning solution for the Spaceship Titanic competition on Kaggle. The task is to predict whether passengers were transported to an alternate dimension based on their personal records and travel details. The model is built using Python, leveraging libraries such as `pandas`, `scikit-learn`, and `numpy` for data processing and classification.

## Overview

The Spaceship Titanic dataset, set in the year 2912, involves an interstellar passenger liner that collided with a spacetime anomaly, transporting nearly half of its 13,000 passengers to an alternate dimension. The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, and model training to classify passengers as "transported" or "not transported."

## Features

- **Data Preprocessing**: Handles missing values, encodes categorical variables, and engineers features (e.g., extracting deck/side from the "Cabin" column).
- **EDA**: Visualizes distributions of numerical features (e.g., Age, RoomService) and categorical variables (e.g., HomePlanet, Destination).
- **Model Training**: Implements classification models (e.g., RandomForestClassifier, Logistic Regression, DecisionTreeClassifier, XBGClassifier and LGBMClassifier ) to predict passenger outcomes.
- **Evaluation**: Assesses model performance using accuracy and cross-validation.

## Requirements

To run this project, you need the following dependencies:
- Python 3.8 or higher
- `pandas` (>=1.3.0)
- `numpy` (>=1.21.0)
- `scikit-learn` (>=1.0.0)
- `matplotlib` (optional, for visualizations)
- `seaborn` (optional, for advanced plotting)

Install the dependencies using pip:
```bash
pip install -r requirements.txt