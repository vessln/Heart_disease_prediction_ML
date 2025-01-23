# Machine learning project - Heart disease prediction 

Predictive tools are crucial for identifying individuals at higher risk of developing heart disease. This allows early intervention or prevention. \
In this project I use Logistic Regression, Decision Tree, Random Forest Classifier, XGBoost and SVM. I selected these algorithms for their effectiveness in binary classification. 
The data used is from two datasets with features such as blood indicators, health metrics and lifestyle habits, all of which are related to heart disease. 
I merged them into one dataset and made EDA to understand the underlying structure and patterns in the datasets.
There is a class imbalance that can lead to biased model performance, favoring the majority class, so I use SMOTE (Synthetic Minority Oversampling Technique). \
Hyperparameter optimization is done with Optuna library. XGBoost shows the best overall performance, especially in terms of ROC_AUC and F1-score, making it the most robust model for this task.   For better understanding of the model decision-making process i analyse feature importances.
