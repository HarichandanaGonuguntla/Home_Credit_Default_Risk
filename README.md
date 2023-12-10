## Home Credit Default Risk

Home Credit is a global financial institution with a specialization in providing loans to individuals who have limited or inadequate credit histories. Their primary objective is to advance financial inclusion by offering easily accessible financial services to disadvantaged communities. Home Credit is known for its innovative financing solutions, utilizing unconventional data sources and alternative methods for assessing creditworthiness. Their customer-centric approach and streamlined lending process empower individuals to make significant purchases and establish a favorable credit record. Home Credit mitigates the lending risks associated with borrowers who have less-than-ideal credit histories through the use of advanced risk management models. In essence, they are committed to democratizing access to financial services and creating a positive social impact.

### **Business Problem:** ###

**Credit Risk Assessment:** Home Credit Group faces the challenge of evaluating the creditworthiness of loan applicants who may not have a traditional credit history. Accurate assessment of credit risk is crucial to minimize loan defaults and associated financial losses.

**Financial Inclusion:** The project seeks to address the problem of financial exclusion by providing loans to individuals who are often underserved by traditional lenders. It aims to offer a positive borrowing experience to those with limited access to credit.

### **Project Goal/Objective:** ###
The goal of the Home Credit Default Risk Kaggle project is to develop a predictive model that accurately assesses the credit default risk of loan applicants. Specifically, the project aims to predict whether a loan applicant is likely to default on their loan, with the broader objective of improving responsible lending practices and financial inclusion for individuals with limited or no credit history.

### **Group's solution to the business problem:** ###
Initially, before the modeling process, data was cleaned, and joined, missing values were replaced, and additional variables were feature-engineered. We have then implemented 3 different machine-learning models namely - Logistic regression, h20 and lime, and XGBoost(Extreme Gradient Boosting), and then chose XGBoost to make home credit default prediction since XGBoost model performed well with the highest accuracy, ROC-AUC score.

XGBoost, a scalable and highly efficient Gradient Boosting framework, is renowned for its performance in classification tasks. The model was trained on various features including demographic data, credit history, transaction and payment records, and social and economic variables. We also implemented hyper-parameter tuning techniques like changing the learning rate, and maximum tree depth to enhance model performance. We also performed cross-validation to assess the model's performance and ensure its generalization to new data.
XGBoost provides a highly efficient implementation of the gradient boosting algorithm, making it suitable for large datasets.The model is fine-tuned to handle the imbalanced nature of credit default datasets.

### **Results:** ###
The model achieved an impressive AUC score of 0.77, indicating a better predictive power and also an accuracy of 92% which means that the model can predict 92% of the instances correctly.
We observed significant improvement over baseline models in terms of both accuracy and AUC.

### **Business Value to the solution:** ###
 Here are some ways in which the XGBoost modeling that we developed can create business value for this problem:
 
1. One of the primary business values is reducing loan defaults. By accurately identifying high-risk applicants, financial institutions can avoid lending to those who are likely to default. This reduces the financial losses associated with non-performing loans. At present, Homecredit is facing losses of around $13.85 billion, equivalent to approximately 7.52% of the total approved loan amount of $184.208 billion. The implementation of the XGBoost model has the potential to accurately predict defaults for 63.5% of these cases, resulting in potential savings of a substantial $8.8 billion.
2. Better risk assessment and reduced loan defaults can lead to increased profitability for financial institutions. They can lend more confidently to low-risk applicants, charge lower interest rates, and attract more customers, all of which contribute to higher profits.
3. Implementing the XGBoost model also promotes a culture of data-driven decision-making within the organization, which can have long-term benefits for strategic planning and operations.
4. Financial institutions can use XGBoost to target marketing efforts more effectively. By identifying potential customers who are likely to be creditworthy, they can focus their marketing campaigns on individuals who are more likely to apply for and be approved for loans.
5. Institutions that excel in credit risk modeling using XGBoost can gain a competitive advantage. They can attract more customers, partners, and investors by showcasing their ability to make informed lending decisions and manage risk effectively.

### **My contribution to the project:** ###
I was involved in the heavy-lifting part of the project. I have done the data preprocessing, missing data calculation, imputation, feature Engineering, different datasets(bureau, bureau balance, previous application) aggregation for predictions, and Modeled using XGBoosting multiple times using different parameters and datasets.

### **Difficulties encountered during the project implementation:** ###
1. The first difficulty was handling the data imbalance. Here the number of non-default cases far exceeded the default cases. We tried to avoid this by implementing the undersampling technique.
2. Properly understanding the dataset and performing comprehensive EDA was another challenge given the large amount of data.
3. Overfitting was another major issue we dealt with and we successfully overcame this by implementing cross-validation.
4. Finding the optimal hyperparameters for our XGBoost model was time-consuming and computationally intensive. We experimented with various combinations of learning rate and tree depth and selected the optimal ones.

### **Learnings from the project implementation:** ###
1. Dealing with real-world data often requires extensive data preprocessing. From this project I learned how to effectively handle missing values, and encode categorical variables.
2. I also learned how to handle imbalanced data and perform feature engineering.
3. I learned how to evaluate different machine learning algorithms, evaluate their performance, and choose the best model suitable for the task.
4. The importance of cross-validation for estimating model performance and avoiding overfitting has been a great learning for me.
5. I learned how to choose and interpret appropriate evaluation metrics, and how to effectively communicate the findings, model results, and recommendations to stakeholders.







