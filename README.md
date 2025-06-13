# Titanic Survival Prediction

This project analyzes the Titanic dataset and builds a model to predict the survival of passengers. It includes steps for data cleaning, exploratory data analysis (EDA), feature engineering, and model evaluation.

i will try to add different modles till i get 100 percent acuracy on unseen data
---

## Table of Contents

- [Introduction](#introduction)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Features](#features)  
- [Dependencies](#dependencies)  
- [Configuration](#configuration)  
- [Documentation](#documentation)  
- [Examples](#examples)  
- [Troubleshooting](#troubleshooting)  
- [Contributors](#contributors)  
- [License](#license)  

---

## Introduction

This project utilizes the Titanic dataset from Kaggle. The goal is to analyze data trends and train a classification model to predict survival based on attributes like age, gender, fare, and more.

---

## Installation

1. Install the required Python packages:

   ```bash
   pip install pandas numpy matplotlib seaborn sklearn
   ```

---

## Usage

1. Place `train.csv` in the root directory of the project.
2. Launch Jupyter Notebook:

   ```bash
   jupyter notebook Logistic.ipynb
   ```

---

## Features

* Exploratory data analysis with plots  
* Data cleaning: handling missing values, converting categorical to numerical  
* Feature selection and engineering  
* Logistic Regression classification model  
* Accuracy evaluation using scikit-learn  

---

## Dependencies

* pandas  
* matplotlib  
* seaborn  
* numpy  
* scikit-learn  
* Jupyter Notebook  

---

## Configuration

* **Input file**: `train.csv`  
* **Model**: Logistic Regression from scikit-learn  
* **Test Size**: 20%  
* **Random State**: 0  

---

## Documentation

* Data visualization includes histograms and box plots for the `Age` feature  
* Encodes `Sex` and `Embarked` columns  
* Missing values in `Age` filled with the mean  

---

## Examples

* Visualize the age distribution of passengers:

  ```python
  sns.histplot(data=df['Age'], bins=10, kde=True)
  ```

* Train the logistic regression model:

  ```python
  classifier = LogisticRegression()
  classifier.fit(X_train, y_train)
  ```

---

## Troubleshooting

* Ensure `train.csv` is in the correct directory  
* Confirm that all dependencies are installed via `pip`  

---

## Contributors

* [M.SRIKAR VARDHAN](https://github.com/M-SRIKAR-VARDHAN)

---

## License

This project is licensed under the MIT License.
