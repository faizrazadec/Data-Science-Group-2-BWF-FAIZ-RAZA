# Evaluation Techniques for Classification Models

## Objective
The aim of this task is to explore and understand various evaluation techniques for classification models. These techniques help assess the performance of models and ensure they make accurate predictions.

## Evaluation Techniques

### 1. Confusion Matrix
A confusion matrix is a table that summarizes the performance of a classification model. It shows the counts of true positives (TP), true negatives (TN), false positives (FP), and false negatives (FN). The confusion matrix provides a detailed breakdown of how well the model is performing, including:

- **True Positives (TP)**: Correctly predicted positive instances.
- **True Negatives (TN)**: Correctly predicted negative instances.
- **False Positives (FP)**: Incorrectly predicted positive instances (Type I error).
- **False Negatives (FN)**: Incorrectly predicted negative instances (Type II error).

### 2. Accuracy
Accuracy is the ratio of correctly predicted instances (both true positives and true negatives) to the total number of instances. It gives a general sense of how often the model is correct:

\[ \text{Accuracy} = \frac{TP + TN}{TP + TN + FP + FN} \]

### 3. Precision
Precision measures the accuracy of positive predictions, defined as the ratio of true positives to the sum of true positives and false positives:

\[ \text{Precision} = \frac{TP}{TP + FP} \]

### 4. Recall (Sensitivity)
Recall, also known as sensitivity or true positive rate, measures the ability of the model to identify all positive instances. It is the ratio of true positives to the sum of true positives and false negatives:

\[ \text{Recall} = \frac{TP}{TP + FN} \]

### 5. F1 Score
The F1 Score is the harmonic mean of precision and recall, providing a balanced measure especially useful when dealing with imbalanced datasets:

\[ \text{F1 Score} = 2 \times \frac{\text{Precision} \times \text{Recall}}{\text{Precision} + \text{Recall}} \]

### 6. ROC Curve
The Receiver Operating Characteristic (ROC) curve is a graphical representation of the true positive rate (recall) versus the false positive rate at various threshold settings. It helps evaluate the trade-offs between true positives and false positives.

### 7. AUC (Area Under the Curve)
The Area Under the ROC Curve (AUC) measures the overall performance of the classification model. An AUC of 1 indicates a perfect model, while an AUC of 0.5 suggests no discrimination ability:

- **AUC = 1**: Perfect model.
- **AUC = 0.5**: No better than random guessing.

### 8. Cross-Validation
Cross-validation is a technique that splits the dataset into multiple folds, training and testing the model on different subsets. This provides a more robust estimate of model performance, reducing the risk of overfitting.

### 9. Classification Report
A classification report provides a summary of precision, recall, F1 score, and support (the number of true instances) for each class. It offers a comprehensive view of the model’s performance across different classes.
