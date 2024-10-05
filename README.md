# 🌟 Gold Price Regression with LazyPredict 🌟

## 📚 Table of Contents
- [🌟 Gold Price Regression with LazyPredict 🌟](#-gold-price-regression-with-lazypredict-)
  - [📚 Table of Contents](#-table-of-contents)
  - [📜 Overview](#-overview)
  - [🔍 Introduction](#-introduction)
  - [📊 Dataset](#-dataset)
  - [💻 Installation](#-installation)
  - [🔧 Workflow](#-workflow)
    - [🗂️ Data Preprocessing](#️-data-preprocessing)
    - [📈 Model Evaluation with LazyPredict](#-model-evaluation-with-lazypredict)
    - [📊 Visualization of Results](#-visualization-of-results)
    - [🏆 Choosing the Best Model](#-choosing-the-best-model)

## 📜 Overview
This notebook demonstrates how to use the LazyPredict library for quickly evaluating multiple regression models on the task of predicting gold prices. It provides a streamlined approach to comparing model performance, focusing on metrics such as R-Squared, RMSE (Root Mean Squared Error), and Time Taken.

## 🔍 Introduction
Predicting gold prices is challenging due to the complex and volatile nature of financial markets. This notebook leverages LazyPredict to automatically train and evaluate various regression models, providing a quick comparison to identify the best-performing model.

## 📊 Dataset
The dataset used is historical gold prices, which includes features such as:
- **Date**: The date of the record.
- **Gold Price**: The price of gold on that date.
- Various macroeconomic indicators (e.g., oil prices, currency exchange rates).

This dataset is crucial for training regression models to predict future gold prices.

**Dataset Link**: [Gold Price Dataset on Kaggle 🥇](https://www.kaggle.com/datasets/cvergnolle/gold-price-and-relevant-metrics)

## 💻 Installation
To run this notebook, you need the following Python libraries:
- `pandas` 📊
- `scikit-learn` 🔍
- `LazyPredict` ⚡
- `matplotlib` 📈
- `seaborn`



## 🔧 Workflow

### 🗂️ Data Preprocessing
The notebook begins by loading and preprocessing the dataset. Key steps include:
- Handling missing values. ❌
- Feature engineering. 🛠️
- Splitting the data into training and testing sets. 📉📈

### 📈 Model Evaluation with LazyPredict
LazyPredict evaluates various regression models, simplifying the process of fitting and comparing their performance metrics:
- **R-Squared**: Measures how well the model explains the variance in the target variable. 📊
- **RMSE**: Indicates the average error of the model's predictions. 📉
- **Time Taken**: The computational time required for each model. ⏱️

### 📊 Visualization of Results
The notebook includes visualizations to compare model performance, such as:
- Bar plots for R-Squared, RMSE, and Time Taken. These help identify models that balance accuracy and efficiency. 📊✨

### 🏆 Choosing the Best Model
The notebook concludes with a method to select the best model based on a combination of R-Squared and RMSE, highlighting the best model for predicting gold prices. 🥇

**Notebook Link**: [Gold Price Regression with LazyPredict on Kaggle 📜](https://www.kaggle.com/code/omarnasser7/gold-price-regression-with-lazypredict)
