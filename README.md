# growth_link_assignment
**Titanic Survival Prediction Project**

This project focuses on predicting whether a passenger survived the Titanic disaster using various machine learning models. The dataset contains features like age, gender, ticket class, fare, and cabin information. The goal is to preprocess the data, build machine learning models, and evaluate their performance for this binary classification task.

**Dataset**
The dataset consists of features such as:
Pclass: Passenger class (1st, 2nd, 3rd)
Sex: Gender (Male, Female)
Age: Age in years
SibSp: Number of siblings or spouses aboard the Titanic
 Parch: Number of parents or children aboard the Titanic
Fare: Passenger fare
Embarked: Port of Embarkation

**Project Steps**
1. Data Preprocessing:
Missing Values: Handled missing values in the `Age`, `Fare`, and `Embarked` columns.
Encoding:Converted categorical variables like `Sex` and `Embarked` into numerical values using one-hot encoding.
Normalization:Normalized continuous variables (`Age`, `Fare`) to bring them to a comparable scale.
2. Feature Selection:Selected key features: Pclass,Sex,Age,SibSp,Parch,Fare, and Embarked for training the models.

**Model Training:**
Built and evaluated the following machine learning models:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - Support Vector Machine (SVM)
  - K-Nearest Neighbors (KNN)
  - Naive Bayes
Used k-fold cross-validation to ensure robust evaluation of the models.

**Model Evaluation:**
**Logistic Regression:**
Train Accuracy (Cross-Validated): 1.0000

Train Precision (Cross-Validated): 1.0000

Train F1-Score (Cross-Validated): 1.0000

Test Accuracy: 1.0000

Test Precision: 1.0000

Test F1-Score: 1.0000

Test ROC-AUC: 1.0000

**Decision Tree:**
Train Accuracy (Cross-Validated): 1.0000

Train Precision (Cross-Validated): 1.0000

Train F1-Score (Cross-Validated): 1.0000

Test Accuracy: 1.0000

Test Precision: 1.0000

Test F1-Score: 1.0000

Test ROC-AUC: 1.0000

**Random Forest:**
Train Accuracy (Cross-Validated): 1.0000

Train Precision (Cross-Validated): 1.0000

Train F1-Score (Cross-Validated): 1.0000

Test Accuracy: 1.0000

Test Precision: 1.0000

Test F1-Score: 1.0000

Test ROC-AUC: 1.0000

**SVM:**
Train Accuracy (Cross-Validated): 0.9970

Train Precision (Cross-Validated): 1.0000

Train F1-Score (Cross-Validated): 0.9957

Test Accuracy: 0.9881

Test Precision: 1.0000

Test F1-Score: 0.9851

Test ROC-AUC: Not available for this model

**KNN:**
Train Accuracy (Cross-Validated): 0.9940

Train Precision (Cross-Validated): 1.0000

Train F1-Score (Cross-Validated): 0.9915

Test Accuracy: 0.9881

Test Precision: 1.0000

Test F1-Score: 0.9851

Test ROC-AUC: 1.0000

**Naive Bayes:**
Train Accuracy (Cross-Validated): 1.0000

Train Precision (Cross-Validated): 1.0000

Train F1-Score (Cross-Validated): 1.0000

Test Accuracy: 1.0000

Test Precision: 1.0000

Test F1-Score: 1.0000

Test ROC-AUC: 1.0000

**Conclusion**
All models performed exceptionally well, with Logistic Regression, Decision Tree, Random Forest, and Naive Bayes achieving perfect accuracy, precision, and F1-Scores on both training and test sets. This suggests that these models fit the data perfectly but may be overfitting. SVM and KNN also showed strong performance with slightly lower F1-Scores, indicating they may generalize better. Overall, while the models performed well, further tuning and evaluation of overfitting are recommended.
