# K-NN Classifier for Magic04 Dataset

This repository contains a Python implementation of a K-NN (K-Nearest Neighbors) classifier applied to the Magic04 dataset. The dataset consists of features related to high-energy gamma-ray and hadron events, with the goal of classifying them as either gamma-ray (g) or hadron (h).

## Dataset Overview

The original dataset was loaded and balanced to ensure an equal representation of gamma and hadron events. The data was then split into training, validation, and testing sets.

- **Training set:** 70% of the data
- **Validation set:** 15% of the data
- **Testing set:** 15% of the data

## Applying K-NN Classifier

The K-NN classifier was applied to the balanced dataset, varying the hyperparameter K. The following metrics were evaluated for different K values:

- Accuracy
- Precision
- Recall
- F1-Score

## Model Comparison and Selection

The performance of the model was assessed for different values of K, ranging from 1 to 1000. Metrics for each K value were stored, and a comparison was made to identify the best model based on accuracy and F1-Score.

## Results


![image](https://github.com/SaadElDine/K-NN-K-Nearest-Neighbors-classifier-/assets/113860522/f404005d-3c4f-4e88-9c0d-dcd3ec410684)



### Best Model (Accuracy):

- K Value: 5
- Accuracy: 76.22%
- Precision: 73.06%
- Recall: 82.39%
- F1-Score: 77.45%

### Best Model (F1-Score):

- K Value: 5
- Accuracy: 76.22%
- Precision: 73.06%
- Recall: 82.39%
- F1-Score: 77.45%

## Confusion Matrix of Best Model

The confusion matrix for the best model (K = 5) is as follows:

![image](https://github.com/SaadElDine/K-NN-K-Nearest-Neighbors-classifier-/assets/113860522/addd78b0-b9ac-4ecb-b5f3-ba0fedad0e99)
