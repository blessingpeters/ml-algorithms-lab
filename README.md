# ML — Machine Learning Coursework & Practice

This repository contains my hands-on machine learning assignments. Each folder
represents a session/topic covered in class, containing only my own assignment
work based on what was taught.

## 📁 Repository Structure

```
ML/
├── 2.Classification Metrics & ML Workflow/
│   └── Assignment_2_Classification_Metrics.ipynb
├── 3.KNN/
│   └── Assignment_3_KNN_Diabetes_Experiment.ipynb
├── 4.SVM/
│   └── Assignment_4_Model_Comparison.ipynb
├── 5.Decision Tree Investigation/
│   └── Assignment_5_Decision_Tree_Investigation.ipynb
├── 6.Decision Trees for Regression/
│   └── Assignment_6_Tree_Based_Prediction.ipynb
├── 7.Random Forest/
│   └── Assignment_7_Decision_Tree_vs_Random_Forest.ipynb
├── 8.Gradient Boosting(XGBoost)/
│   └── Assignment_8_Model_Comparison_LogReg_RF_XGBoost.ipynb
└── README.md
```

## 📚 Topics Covered

### 2. Classification Metrics & ML Workflow
- Covered the full supervised machine learning workflow: data loading, train/test
  split, model training, prediction, and evaluation.
- Explored key classification metrics: **Accuracy, Precision, Recall, F1-Score,
  and Confusion Matrix**.
- Discussed when to prioritize Precision vs Recall depending on the real-world
  cost of false positives vs false negatives.
- Practiced interpreting a confusion matrix and classification report.

### 3. K-Nearest Neighbors (KNN)
- Trained a KNN classifier on the **Pima Indians Diabetes dataset**.
- Compared performance across different values of **K** (1, 3, 5, 7, 9).
- Investigated overfitting (K=1) vs underfitting (large K).
- Identified the best K based on Testing Accuracy and F1-Score.
- Demonstrated the importance of **feature scaling** for distance-based models.

### 4. Support Vector Machines (SVM)
- Compared **Logistic Regression, KNN, and SVM (RBF kernel)** on the same dataset.
- Used the `make_circles` dataset to visualize non-linear decision boundaries.
- Generated a full metrics comparison table: Accuracy, Precision, Recall, F1-Score, ROC-AUC.
- Explained the Kernel Trick, margin maximization, and why SVM generalizes well on non-linear data.

### 5. Decision Trees (Classification)
- Built Decision Tree classifiers on the **Iris dataset**.
- Trained multiple trees using different values of `max_depth`.
- Compared Training vs Testing accuracy to identify the point where overfitting begins.
- Visualized the best-performing tree and explained why unrestricted trees overfit.

### 6. Decision Trees for Regression
- Built a Decision Tree Regressor to predict a continuous target variable.
- Compared model performance across different `max_depth` values.
- Evaluated regression performance using metrics such as MAE, MSE, and R².
- Investigated how tree depth affects underfitting/overfitting in a regression context.

### 7. Random Forest
- Compared a single **Decision Tree** against a **Random Forest** on the same dataset.
- Explored how ensembling multiple trees (bagging) reduces overfitting and variance.
- Compared model performance and stability between the two approaches.
- Discussed why Random Forest generally generalizes better than a single Decision Tree.

### 8. Gradient Boosting (XGBoost)
- Compared **Logistic Regression, Random Forest, and XGBoost** on the same dataset.
- Explored how gradient boosting builds trees sequentially to correct previous errors.
- Generated a full classification metrics comparison table across all three models.
- Discussed the trade-offs between boosting and bagging-based ensemble methods.

## 🛠️ Tools & Libraries
- Python
- pandas, numpy
- matplotlib
- scikit-learn (`sklearn`)
- xgboost

## 🎯 Purpose
This repository is a personal learning log for practicing supervised and unsupervised
machine learning concepts — classification metrics, model evaluation, hyperparameter
tuning, ensemble methods, and model comparison — through hands-on Jupyter notebook
assignments.