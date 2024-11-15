Lets Understand Recently I have performed Dealing with Imbalanced Data in machine learning Techniques get insights from the data in Python environment

-  Author : Rahul11
-  importing intianl stages of python requried libraries
-  Reading the csv file using pandas

Oversampling:
-  Random Oversampling: This duplicates samples from the minority class until it matches the majority class.
-  Explanation: Random oversampling duplicates minority class samples, which can help balance the dataset but may lead to overfitting.

SMOTE (Synthetic Minority Over-sampling Technique):
-  SMOTE : SMOTE creates synthetic samples by interpolating between existing minority class samples
-  Explanation: SMOTE addresses overfitting by creating new samples instead of duplicating. However, it may create synthetic samples that aren’t representative of real data.

Undersampling:
-  Random Undersampling: Randomly removes samples from the majority class
-  Explanation: Random undersampling reduces dataset size and may remove useful information, impacting model performance.

Evaluation Metrics:
-  Confusion Matrix: Shows the performance of the model on both classes.
-  Explanation: AUC-ROC provides a single score to evaluate model performance across both classes, with higher values indicating better performance on the minority class.
