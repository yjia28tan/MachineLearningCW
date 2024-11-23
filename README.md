# 6006CEM Machine Learning and Related Applications Coursework

This repository contains the implementation of two fundamental machine learning tasks: regression and classification, as part of a coursework project.

## Project Overview

- **Regression Task**: Predicts benzene concentration in the air using Linear Regression, Random Forest, Ridge and Lasso Regression models.
- **Classification Task**: Classifies text data into emotional states using a Support Vector Machine (SVM), and Logistic Regression.

## Datasets

- **Regression Problem**: [Air Quality Dataset](https://archive.ics.uci.edu/dataset/360/air+quality)
- **Classification Problem**: [Emotions Dataset](https://www.kaggle.com/datasets/nelgiriyewithana/emotions/data)

## Key Features

1. **Regression Task**
   - Predicts continuous benzene concentration values using environmental data.
   - Includes data preprocessing, exploratory data analysis (EDA), and model evaluation using metrics like Mean Squared Error (MSE).

2. **Classification Task**
   - Predicts emotional states (e.g., sadness, joy, love, anger, fear, surprise) from text data.
   - Implements data cleaning, feature vectorization, and classification using SVM.

3. **Model Selection**
   - Ridge and Lasso Regression were selected for the regression task.
   - Support Vector Machine (SVM) was chosen for the classification task.

## Repository Structure

- [Classification Directory](https://github.com/yjia28tan/MachineLearningCW/tree/main/Classification)
    - This directory contains the dataset in a CSV file and a Jupyter notebook with the source code to train the classification models.

- [Regression Directory](https://github.com/yjia28tan/MachineLearningCW/tree/main/Regression)
    - This directory contains the dataset in an Excel file (`AirQualityUCI.xlsx`) and multiple Jupyter notebooks for training and evaluation:
        - `Regression.ipynb`: Initial model training and evaluation choosing the target variable - 'CO(GT)'.
        - `Regression - Benzene target.ipynb`: Initial model training and evaluation (Bezene as target variable).
        - `Regression - Benzene2.ipynb`: Intermediate tuning and additional analysis.
        - `Regression - Benzene3.ipynb`: **Final model training and evaluation after tuning and retraining.**
        

    - [Final Model Training Notebook](https://github.com/yjia28tan/MachineLearningCW/blob/main/Regression/Regression%20-%20Benzene3.ipynb)

## Results

- **Regression Task**: Achieved accurate predictions for benzene concentration with Ridge and Lasso Regression models.
- **Classification Task**: Successfully categorized emotional states with high accuracy using SVM.
