# Logistic-Regression


Logistic Regression was performed on the dataset to predict a student's chance of getting a job placement  based on two features: IQ and CGPA. The goal was to classify students as either Yes (1) or No (0) using these  indicators.


The model did **not perform better** even after oversampling the minority class using SMOTE.  
This suggests that **logistic regression is not well-suited for this particular imbalanced dataset**.

Despite balancing the data, the model struggled to separate the classes effectively, as shown by:
- Modest precision and recall
- Low overall accuracy
- F1-scores indicating weak predictive power

➡️ **Conclusion**: Logistic Regression may not be the best choice for this classification task. A more powerful model (e.g., Random Forest, XGBoost, or SVM) might yield better performance on this imbalanced dataset.

