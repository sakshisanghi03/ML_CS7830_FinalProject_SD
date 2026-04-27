# Credit Card Fraud Detection using Machine Learning

This project focuses on detecting fruadulent credit card transactions using machine learning models on a highly imbalanced real-world dataset.


-- 


## Dataset 
- Source :Kaggle Credit Card Fruad Dataset
- Total transactions: **284,807**
- Fraud Cases : **~0.17% (highly imbalanced)**
- Features are anoymized using PCA (`V1-V28`)


-- 


## Approach 
-  Verified dataset  (no missing or duplicate values)
-  Handled imblance using:
    - **SMOTE (oversampling)**
    - **Class weighting**
-  Split data inot ** 80% training / 20% testing**
- Applied **feature scaling** where required


--

## Model Used
- Logistic Regression(baseline)
- Linear SVM
- XGBoost (best performing model)


--


## Evaluation Metrics

Since the dataset is highly imbalanced, accuracy alone is not reliable.  
We used the following metrics:

- **Accuracy** – Overall correctness of predictions  
- **Precision** – How many predicted fraud cases are actually fraud  
- **Recall** – How many actual fraud cases are correctly detected  
- **F1 Score** – Balance between precision and recall  
- **AUC-ROC** – Model performance across different thresholds


--


## Team Collaboration

This project was developed collaboratively using a shared GitHub repository.  
All team members were added as collaborators, allowing us to contribute, track changes, and manage the project efficiently.


--


## Team Members
- Sakshi Sanghi  
- Dharani Manne
