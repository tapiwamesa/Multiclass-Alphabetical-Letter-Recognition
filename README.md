# Letter Recognition using Machine Learning

This project focuses on building and evaluating machine learning models to classify letters (A–Z) based on extracted features. It compares the performance of logistic regression and decision tree classifiers to determine the most accurate and reliable model for this task.

## Project Overview

Letter recognition is a key task in various applications including OCR systems, data entry automation and educational software. The objective of this project is to develop and evaluate models that can accurately classify individual letters from a set of numerical features.

## Models and Performance

Two classification models were trained and tested:

- **Logistic Regression**:
  - Accuracy: 77%
  - Precision: 77%
  - Recall: 76%
  - F1-Score: 76.9%

- **Decision Tree Classifier**:
  - Accuracy: 86%
  - Precision: 86%
  - Recall: 86%
  - F1-Score: 86%

The decision tree model consistently outperformed logistic regression across all evaluation metrics and demonstrated better generalization to unseen test data.

## Key Features

- Confusion matrix analysis to explore classification accuracy per letter
- Detailed evaluation metrics: precision, recall and F1-score
- Visual insights to support model comparison
- Final model recommendation based on performance

## Requirements

- Python 3.1
- scikit-learn
- pandas
- numpy
- matplotlib
- seaborn
- jupyter (optional, for notebooks)

## Conclusion

This project highlights the benefits of model selection in classification tasks. The decision tree classifier significantly improved the performance of letter recognition over logistic regression, making it the preferred model for this dataset.
