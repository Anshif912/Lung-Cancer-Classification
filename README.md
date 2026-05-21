# Lung Cancer Classification using Decision Tree

## Overview

This project uses a Decision Tree Classifier to predict lung cancer cases based on survey data. The Decision Tree model uses health and behavioral features to classify whether someone has lung cancer. The Decision Tree Classifier is a choice for this project because it is easy to understand and interpret.

## Objective

* Build a classification model using a Decision Tree Classifier

* Learn about entropy and information gain and the Gini index

* Check how well the Decision Tree model works using metrics

## Concepts Used

* The Decision Tree Algorithm is used to classify lung cancer cases

* Entropy is a measure of how uncertain we're about a prediction

* Information Gain is the difference in entropy before and after a split

* The Gini Index is a measure of how a split separates the data

We want to minimize entropy and the Gini Index and maximize Information Gain for splits in the Decision Tree model.

## Dataset

* The dataset used is the Lung Cancer Survey Dataset

* The dataset is loaded using Pandas

* The dataset contains patient-related features like smoking habits and anxiety and fatigue and breathing issues and alcohol consumption

### Target Variable

* The target variable is `LUNG_CANCER`

## Data Preprocessing

* The dataset is checked for missing values

* Categorical data is converted using Label Encoding for `GENDER` and `LUNG_CANCER`

* A correlation analysis is done using a heatmap to see how the features are related to each

## Feature Selection

The following features are chosen for training the Decision Tree model:

* `YELLOW_FINGERS`

* `ANXIETY`

* `GENDER`

* `ALCOHOL CONSUMING`

* `FATIGUE`

* `SHORTNESS OF BREATH`

These features are chosen because they are relevant to lung cancer cases.

## Model Building

* The algorithm used is the Decision Tree Classifier

* The criterion used is entropy

```python

DecisionTreeClassifier(criterion='entropy' random_state=42)

```

The Decision Tree Classifier is a choice for this project because it is easy to understand and interpret.

## Train-Test Split

* 80 percent of the data is used for training

* 20 percent of the data is used for testing

This is a split because it gives us a large enough dataset to train the model and a small enough dataset to test the model.

## Model Evaluation

The Decision Tree model is evaluated using:

* Accuracy Score

* Confusion Matrix

* Classification Report

These metrics give us an idea of how well the Decision Tree model is performing.

## Visualization

* A correlation heatmap is used to visualize the correlation, between the features

* A Decision Tree visualization is used to visualize the Decision Tree model

These visualizations help us understand the data and the model better.

## Workflow

1. Load the dataset

2. Preprocess the data

3. Encode categorical variables

4. Choose features

5. Split the dataset

6. Train the Decision Tree model

7. Evaluate the performance of the Decision Tree model

8. Visualize the results

Thiss a good workflow because it gives us a clear idea of what we need to do to build and evaluate the Decision Tree model.

## Tools and Libraries

* Python is used as the programming language

* Pandas is used for data manipulation

* NumPy is used for computations

* Matplotlib is used for visualization

* Seaborn is used for visualization

* Scikit-learn is used for machine learning

These tools and libraries are choices because they are easy to use and give us a lot of functionality.

This project shows how a Decision Tree Classifier can classify lung cancer cases using survey data. It highlights the importance of choosing features and preprocessing and understanding decision tree splitting criteria for the Decision Tree model.

## Author

* Anshif H
