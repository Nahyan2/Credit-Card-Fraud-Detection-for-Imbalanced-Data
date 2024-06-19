                                            **Credit Card Fraud Detection**

**Overview**
This project focuses on detecting fraudulent credit card transactions using machine learning techniques. 
The dataset used is from Kaggle, containing anonymized credit card transactions labeled as fraudulent or genuine.

**Dataset**
The dataset (creditcard.csv) is loaded using Pandas, providing a detailed overview of the data structure and summary statistics.

**Libraries Used**
Data Handling: Pandas for data manipulation and CSV file I/O.
Machine Learning: TensorFlow for building and training models.
Visualization: Matplotlib and Seaborn for data visualization.
Dimensionality Reduction: TSNE, PCA, and TruncatedSVD for feature extraction and visualization.

**Classifiers Explored**
Several classifiers are explored for their effectiveness in fraud detection:
1. Logistic Regression
2. Support Vector Machine (SVM)
3. K-Nearest Neighbors (KNN)
4. Decision Tree
5. Random Forest

**Data Preprocessing**
The dataset is preprocessed to handle class imbalance using techniques like:
1.SMOTE (Synthetic Minority Over-sampling Technique)
2.NearMiss for under-sampling

**Evaluation Metrics**
Performance metrics used to evaluate models include:
1.Precision
2.Recall
3.F1-score
4.ROC AUC score
5.Accuracy

**Cross-Validation**
1.K-Fold and Stratified K-Fold cross-validation methods are utilized to ensure robust model evaluation.
