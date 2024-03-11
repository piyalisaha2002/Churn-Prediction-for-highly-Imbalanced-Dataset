# Churn Prediction for Highly Imbalanced Dataset

This project focuses on addressing the challenge of highly imbalanced datasets in churn prediction using a combination of ADASYN sampling and Weighted Random Forest algorithm. By exploring various methods to handle class imbalance, we aim to improve the performance of churn prediction models.

## Overview

The project evaluates the performance of Random Forest, Random Forest trained on ADASYN sampled data, and Random Forest trained on Weighted Random Forest for four different datasets characterized by varying levels of class imbalance. The minority class percentages in these datasets range from 2% to 36%.

## Methodology

1. **Data Exploration**: 
   - Analyze the imbalance ratio in each dataset.
   - Understand the distribution of features and the target variable.

2. **Model Training**:
   - Train Random Forest classifier on the original imbalanced dataset.
   - Apply ADASYN sampling to the minority class to balance the dataset and train Random Forest.
   - Use Weighted Random Forest, assigning higher weights to minority class samples during training.

3. **Evaluation**:
   - Measure the performance of each model using metrics such as accuracy, precision, recall, F1-score, and confusion matrix.
   - Compare the results obtained from different approaches to handle class imbalance.

## Datasets

- Four telecom chrun datasets with varying levels of class imbalance.
- Minority class percentages: 2%, 1.7%, 16%, and 36%.

## Results

- **Testing Accuracy**: Observe significant improvements in testing accuracy when using ADASYN sampling and Weighted Random Forest compared to the baseline Random Forest model.
- **Confusion Matrix Metrics**: Notice enhanced performance in terms of precision, recall, and F1-score, particularly for the minority class.

## Conclusion

- The proposed framework, employing ADASYN sampling and Weighted Random Forest, demonstrates robustness in handling highly imbalanced datasets for churn prediction.
- The approach helps the model learn better from the minority class samples, resulting in improved predictive performance.
- This project underscores the importance of addressing class imbalance issues in churn prediction tasks and provides effective techniques to mitigate such challenges.


