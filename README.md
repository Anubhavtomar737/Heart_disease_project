# Heart_disease_project
Project Summary

This project explored the use of machine learning to predict heart disease risk using the classic UCI Heart Disease dataset.  The dataset combined data from four different locations (Cleveland, Hungary, Switzerland, and Long Beach V), and included a range of patient attributes like age, sex, cholesterol levels, and ECG results.

Methodology

Model Selection: Several models were tested, including Logistic Regression, Random Forest, Catboost, and XGBoost. Logistic Regression ultimately proved the most accurate for this specific dataset.
Evaluation Metrics: Model performance was assessed using a combination of metrics:
ROC curve and AUC score to visualize and quantify the model's ability to discriminate between healthy and diseased cases.
Confusion matrix to understand true positives, true negatives, false positives, and false negatives.
Classification report providing precision, recall, and F1-score, offering a balanced view of the model's predictive power.
Key Findings

Logistic Regression Performance: Logistic Regression stood out as the most effective model, demonstrating strong predictive accuracy for heart disease risk.
Further Improvement: Catboost and XGBoost showed potential for even higher accuracy, indicating the dataset's suitability for more complex models.
Future Directions

Feature Importance Analysis: Investigating which features are most influential in the model's predictions can provide valuable medical insights.
Model Explainability: Techniques like SHAP values could be used to explain how the model makes decisions, increasing trust and transparency.
Comparison with Newer Datasets: Evaluating the model on more recent datasets could reveal how heart disease risk factors and prediction methods have evolved over time.
