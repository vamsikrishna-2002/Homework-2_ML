# VAMSI KRISHNA YARRAGUNTA (700772692)
Problem 7: Decision Tree on Iris Dataset  
Task:  
  ->rain DecisionTreeClassifier with different depths (max_depth = 1, 2, 3).  
  ->Report training and test accuracy.  
  ->Discuss signs of underfitting vs. overfitting.  
Key Points:  
  ->Depth=1: High bias → underfits (low accuracy).  
  ->Depth=3: Captures more complexity → risk of overfitting.  
  ->Depth=2: Balanced trade-off.  


Problem 8: kNN Decision Boundaries  
Task:  
  ->Train KNeighborsClassifier with k=1,3,5,10 using only two Iris features: sepal length and sepal width.  
  ->Plot decision boundaries for each k.  
  ->Compare how boundaries change.  
Key Points:  
  ->k=1: Very wiggly boundaries (overfitting).  
  ->k=10: Smooth boundaries, but may misclassify local clusters (underfitting).  
  ->k=3,5: Good balance.  


Problem 9: Performance Evaluation of kNN  
Task:  
  ->Train KNeighborsClassifier with k=5 on Iris dataset.  
  ->Compute confusion matrix.  
  ->Report accuracy, precision, recall, F1 using classification_report.  
  ->Plot ROC curves (one-vs-rest) and compute AUC.  
Key Points  
  ->Confusion matrix shows per-class performance.  
  ->Precision/Recall/F1 provide detailed class-level metrics.  
  ->ROC/AUC provides a threshold-independent evaluation.  
  ->Overall accuracy ≈ high (>90%) due to Iris dataset being well-separated.  
