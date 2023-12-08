## Home Credit Default Risk

### **Business Problems:** ###

**Credit Risk Assessment:** Home Credit Group faces the challenge of evaluating the creditworthiness of loan applicants who may not have a traditional credit history. Accurate assessment of credit risk is crucial to minimize loan defaults and associated financial losses.

**Financial Inclusion:** The project seeks to address the problem of financial exclusion by providing loans to individuals who are often underserved by traditional lenders. It aims to offer a positive borrowing experience to those with limited access to credit.

### **Project Goal/Objective:** ###
The goal of the Home Credit Default Risk Kaggle project is to develop a predictive model that accurately assesses the credit default risk of loan applicants. Specifically, the project aims to predict whether a loan applicant is likely to default on their loan, with the broader objective of improving responsible lending practices and financial inclusion for individuals with limited or no credit history.

### **Group's solution to the business problem:** ###
Initially, before the modeling process, data was cleaned, and joined, missing values were replaced, and additional variables were feature-engineered. We have then implemented 3 different machine-learning models namely - Logistic regression, h20 and lime, and XGBoost(Extreme Gradient Boosting), and then chose XGBoost to make home credit default prediction since XGBoost model performed well with the highest accuracy, ROC-AUC score.

XGBoost, a scalable and highly efficient Gradient Boosting framework, is renowned for its performance in classification tasks. The model was trained on various features including demographic data, credit history, transaction and payment records, and social and economic variables. We also implemented hyper-parameter tuning techniques like changing the learning rate, and maximum tree depth to enhance model performance. We also performed cross-validation to assess the model's performance and ensure its generalization to new data.

### **Key Features:** ###

***Efficiency and Scalability:*** XGBoost provides a highly efficient implementation of the gradient boosting algorithm, making it suitable for large datasets.

***Handling of Imbalanced Data:*** The model is fine-tuned to handle the imbalanced nature of credit default datasets.

### **Results:** ###
The model achieved an impressive AUC score of 0.77, indicating a better predictive power and also an accuracy of 92% which means that the model can predict 92% of the instances correctly.
We observed significant improvement over baseline models in terms of both accuracy and AUC.

### **Business Value to the solution:** ###



### **My contribution to the project:** ###
I was involved in the heavy-lifting part of the project. I have done the data preprocessing, missing data calculation, and imputation, feature Engineering, different datasets(bureau, bureau balance, previous application) aggregation for predictions, and Modeled using XGBoosting multiple times using different parameters and datasets.




### **Difficulties that my group encountered along the way:** ###

### **What you learned in the project:** ###






