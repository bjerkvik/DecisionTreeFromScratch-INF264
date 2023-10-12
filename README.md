# DecisionTreeFromScratch-INF264

This repository contains an implementation of a decision tree classifier from scratch as part of the INF264 course.

## Table of Contents
- [Imports and Data Loading](#imports-and-data-loading)
- [Data Analysis and Preprocessing](#data-analysis-and-preprocessing)
- [Decision Tree Learning Algorithm Implementation](#decision-tree-learning-algorithm-implementation)
- [Adding Gini Index](#adding-gini-index)
- [Reduced-Error Pruning](#reduced-error-pruning)
- [Evaluation of the Algorithm](#evaluation-of-the-algorithm)
- [Comparison to an Existing Implementation](#comparison-to-an-existing-implementation)

## Imports and Data Loading
Essential libraries are imported, and the dataset is loaded.

## Data Analysis and Preprocessing
The dataset is examined to understand the features and labels, check for missing values, and identify potential outliers.

## Decision Tree Learning Algorithm Implementation
The decision tree algorithm is implemented using entropy as the impurity measure. This section includes:
- DecisionNode and Leaf classes for tree construction.
- Functions for entropy, information gain, and tree building.
- The `learn()` function for tree construction.
- The `predict()` function for making predictions.

## Adding Gini Index
Gini index is introduced as an alternative impurity measure to entropy.

## Reduced-Error Pruning
The decision tree's tendency to overfit is addressed by introducing reduced-error pruning.

## Evaluation of the Algorithm
The dataset is split into training, validation, and test sets. The performance of the decision tree model is evaluated using accuracy and F1-score.

## Comparison to an Existing Implementation
The custom decision tree implementation is compared with sklearn's DecisionTreeClassifier in terms of accuracy, F1-score, and training time.

## Dataset
The dataset used in this project is named `wine_dataset.csv` and can be found in the repository.
