# Fraud-Detection-PyTorch
Project: Smart Fraud Detection System using PyTorch

![image](https://github.com/user-attachments/assets/b398ef9d-4a8f-4de9-93d6-8e80a96cd66a)


Dataset : https://www.kaggle.com/datasets/nelgiriyewithana/credit-card-fraud-detection-dataset-2023/data

The fraud detection model was evaluated for its performance on a dataset of 113,726 instances.

Input Features:

id: Unique identifier for each transaction
V1-V28: Anonymized features representing various transaction attributes (e.g., time, location, etc.)
Amount: The transaction amount

Output Label:

Class 0.0 (Non-fraudulent transactions): These are normal, legitimate transactions that are not flagged as fraudulent.

Class 1.0 (Fraudulent transactions): These are transactions identified as fraudulent and flagged by the system.

The model demonstrates high precision, recall, and F1-score for both classes, along with an impressive overall accuracy of 98%. This ensures that the model is effective in detecting fraudulent transactions while minimizing false positives and false negatives.


**Confusion Matrix Insights**

True Negatives (TN): 55,932

False Positives (FP): 818

False Negatives (FN): 1,156

True Positives (TP): 55,820

Observations:

The model demonstrates a high accuracy in both classes with minimal misclassification.

The count of false positives and false negatives is relatively small compared to the true positives and true negatives.

**Classification Report Summary**

Class 0 (Negative Class):

Precision: 98%

Recall: 99%

F1-Score: 98%

Class 1 (Positive Class):

Precision: 99%

Recall: 98%

F1-Score: 98%

Overall Metrics:

Accuracy: 98%

Macro Average:

Precision: 98%

Recall: 98%

F1-Score: 98%

Weighted Average:

Precision: 98%

Recall: 98%

F1-Score: 98%
