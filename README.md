# Random Forest Classifier with Model Evaluation and Feature Importance

This repository contains a Python notebook that demonstrates the use of a Random Forest classifier for a supervised learning problem. The notebook includes training the model, evaluating its performance using multiple metrics, and exploring feature importance.

## Connect with Me

- **LinkedIn:** [https://www.linkedin.com/in/mahshidkhatami-data-analyst/](https://www.linkedin.com/in/mahshidkhatami-data-analyst/)
- **Email:** [khatami.mahshid@gmail.com](mailto:khatami.mahshid@gmail.com)


## Table of Contents

- [Project Overview](#project-overview)
- [Usage](#usage)
- [Model Evaluation](#model-evaluation)
- [Feature Importance](#feature-importance)
- [Dependencies](#dependencies)


## Project Overview
This project focuses on training a Random Forest classifier on a dataset. The key steps include:

1. **Training the model:** We use the Random Forest algorithm to fit the model to the training data.
2. **Evaluating the model:** Predictions are generated using the test set, and various metrics are calculated to assess the model's performance.
3. **Feature Importance:** The notebook also highlights the most important features based on the trained model.

## Usage

## Model Evaluation
The model's performance is evaluated using the following metrics:

- **Accuracy:** The overall correctness of the model.
- **Precision:** The ability of the classifier to not label a negative sample as positive.
- **Recall:** The ability of the classifier to find all the positive samples.

## Feature Importance
You can understand which features contribute the most to the predictions made by the Random Forest model with this code:

```
importances = rf.feature_importances_
indices = np.argsort(importances)[::-1]
```

## Dependencies
The main libraries used in this project include:

- **scikit-learn:** For machine learning algorithms and model evaluation
- **matplotlib:** For visualizing feature importance
- **graphviz:** For visualizing decision trees
- **numpy:** For numerical operations

Install these dependencies using:

```
pip install -r requirements.txt
```