# Customer_churn_prediction
# 📌 Project Description
This project predicts customer churn using machine learning models. Churn prediction is crucial for businesses because retaining existing customers is more cost-effective than acquiring new ones.
The workflow includes data preprocessing, exploratory data analysis (EDA), balancing class imbalance, feature scaling, model training, and evaluation using several ML algorithms.
<br><br>
# 📊 Project Workflow
1) Data Preprocessing
* Cleaning missing and inconsistent values
* Encoding categorical features (e.g., gender, contract type)
* Balancing churn vs non-churn data using SMOTE / oversampling
* Feature scaling for numerical variables

2) Exploratory Data Analysis (EDA)
* Distribution of churn vs non-churn customers
* Feature relationships (age, tenure, charges, etc.) with churn
* Correlation analysis of numerical features

3) Data Splitting
* Train-test split to evaluate model generalization

4) Model Building
* Random Forest
* BernoulliNB
* KNN
* SVM

5) Model Evaluation
* Confusion Matrix
* Classification Report (Precision, Recall, F1-Score)
* Accuracy comparison across models
* ROC Curve / AUC score
<br><br>
# 🛠️ Tools & Libraries
* Python
* Pandas / NumPy – Data preprocessing
* Matplotlib / Seaborn – Data visualization
* Scikit-learn – ML models, train-test split, evaluation metrics
* Imbalanced-learn (SMOTE) – Handling class imbalance
<br><br>
# 🚀 Business Impact
* By identifying customers who are most likely to churn, businesses can:
* Launch targeted retention strategies
* Offer personalized incentives
* Reduce customer acquisition costs
* Improve long-term customer loyalty
