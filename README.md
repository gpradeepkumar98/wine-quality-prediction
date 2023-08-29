# wine-quality-prediction

# Red Wine Quality Classification Project

![Wine Glasses](wine_glasses.jpg)

Welcome to the Red Wine Quality Classification project repository! This project aims to predict whether a given red wine is of "good quality" or not using machine learning techniques. The dataset used for this project is sourced from Kaggle's Red Wine Quality dataset.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Project Steps](#project-steps)
- [Models Used](#models-used)
- [Evaluation Metrics](#evaluation-metrics)
- [Getting Started](#getting-started)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

In this project, I built and evaluated various classification models to predict whether a particular red wine is of "good quality" or not. The quality of the wine is determined by a "quality" score, and for the purposes of this analysis, I transformed the problem into a binary classification task where wines with a score of 7 or higher are considered "good quality," and the rest are labeled as not. The focus was on understanding the factors that contribute to wine quality prediction.

## Dataset

The dataset used for this project is the [Red Wine Quality dataset](https://www.kaggle.com/uciml/red-wine-quality-cortez-et-al-2009) from Kaggle. It contains a set of features that provide information about the wine's properties and chemical composition, along with the quality score assigned to each wine.

## Project Steps

1. Data Loading and Exploration.
2. Data Preprocessing and Cleaning.
3. Binary Classification Labeling.
4. Feature Selection.
5. Model Building and Training.
6. Model Evaluation and Comparison.
7. GitHub Repository Creation.

## Models Used

- Logistic Regression
- Random Forest Classifier
- Xgboost
- naive_bayes
- DecisionTree
- KNN
- Support Vector Classification


## Evaluation Metrics

I assessed the performance of the classification models using metrics such as accuracy and confusion matrix. These metrics provide a comprehensive view of how well the models are predicting the "good quality" label.

## Getting Started

To get started with this project:

1. Install the required dependencies: `pip install -r requirements.txt`

## Dependencies

- Python 3.x
- scikit-learn
- pandas
- seaborn
- ...

## Usage

You can use the code and analysis in this repository to understand the process of building and evaluating classification models for predicting wine quality. Feel free to explore the notebooks, scripts, and documentation.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

