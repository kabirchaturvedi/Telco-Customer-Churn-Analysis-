## README for GitHub Repository: Telco Customer Churn Analysis

# Telco Customer Churn Analysis

Welcome to my GitHub repository for the Telco Customer Churn Analysis project. This project aims to predict customer churn in a telecommunications company using supervised machine learning techniques.

## 1. Introduction
### Purpose
The objective of this project is to analyze customer data to identify factors contributing to churn and to build a predictive model that can accurately classify customers who are likely to churn. This helps in implementing targeted retention strategies.

### Tech Stack
- **Languages and Libraries:** Python, NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn
- **Machine Learning Models:** Logistic Regression, Decision Tree, Random Forest, AdaBoost
- **Data Source:** [Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn)

## 2. Project Scope
This project involves data cleaning, exploratory data analysis (EDA), feature engineering, model training, and evaluation. The primary goal is to develop a robust model that can predict customer churn with high accuracy and F1-score.

## 3. Features
- **Data Cleaning:** Handling missing values, encoding categorical variables, and scaling numerical features.
- **Exploratory Data Analysis:** Visualizing the data to identify trends and relationships between features.
- **Feature Engineering:** Creating new features to improve model performance.
- **Model Training:** Building and evaluating multiple machine learning models to identify the best-performing model.
- **Model Evaluation:** Using accuracy, precision, recall, and F1-score to assess model performance.

## 4. Dataset
The dataset contains information about customer demographics, account information, and service usage. Key features include:
- **CustomerID:** Unique identifier for each customer.
- **Gender:** Gender of the customer.
- **SeniorCitizen:** Whether the customer is a senior citizen.
- **Partner:** Whether the customer has a partner.
- **Dependents:** Whether the customer has dependents.
- **Tenure:** Number of months the customer has stayed with the company.
- **PhoneService:** Whether the customer has phone service.
- **MultipleLines:** Whether the customer has multiple lines.
- **InternetService:** Type of internet service.
- **OnlineSecurity:** Whether the customer has online security.
- **OnlineBackup:** Whether the customer has online backup.
- **DeviceProtection:** Whether the customer has device protection.
- **TechSupport:** Whether the customer has tech support.
- **StreamingTV:** Whether the customer has streaming TV.
- **StreamingMovies:** Whether the customer has streaming movies.
- **Contract:** Type of contract.
- **PaperlessBilling:** Whether the customer has paperless billing.
- **PaymentMethod:** Payment method.
- **MonthlyCharges:** Monthly charges.
- **TotalCharges:** Total charges.
- **Churn:** Whether the customer churned.

## 5. EDA Visualizations
  ### 1)
  <img width="993" alt="image" src="https://github.com/kabirchaturvedi/Telco-Customer-Churn-Analysis-/assets/75251353/11a9a046-7b75-4a3e-85ab-c320de00c228">

  ### 2)
  <img width="994" alt="image" src="https://github.com/kabirchaturvedi/Telco-Customer-Churn-Analysis-/assets/75251353/98c84867-245e-4265-bd7a-f6097cf5aab0">



## 6. Results
The AdaBoost classifier achieved the highest performance with an 89% F1-score and 83% accuracy. The model effectively identifies customers likely to churn, enabling the company to take proactive measures to retain them.
  ### 1) Feature Importance as Determined by the Model
  ![image](https://github.com/kabirchaturvedi/Telco-Customer-Churn-Analysis-/assets/75251353/33a6f8b4-c37c-442a-8ed8-fe154d79d98d)


  ### 2) Confusion Matrix of the AdaBoost Model
  <img width="361" alt="image" src="https://github.com/kabirchaturvedi/Telco-Customer-Churn-Analysis-/assets/75251353/7a8e9361-95d1-45f6-bef0-d15b73602eeb">


## 7. Future Enhancements
- **Feature Expansion:** Incorporating additional features such as customer interactions and service feedback.
- **Model Improvement:** Experimenting with other advanced machine learning techniques and hyperparameter tuning.
- **Deployment:** Developing a web application for real-time churn prediction.

## 8. Conclusion
This project demonstrates the application of supervised machine learning techniques to predict customer churn. The insights gained can help telecommunications companies improve customer retention and reduce churn rates.

## 9. Files in Repository
- **TELCO_CHURN_ANALYSIS_SupervisedLearning_Kabir_Chaturvedi.ipynb:** Jupyter notebook with the complete analysis and model building process.
- **Telco_customer_churn.csv:** Dataset used for the analysis.

## 10. Acknowledgments
I thank my mentors and peers for their valuable feedback and support throughout this project.

Feel free to explore the repository, and don't hesitate to reach out if you have any questions or suggestions. Enjoy exploring the Telco Customer Churn Analysis project!

Happy Coding!

Kabir Chaturvedi

[kabirschaturvedi@gmail.com](mailto:kabirschaturvedi@gmail.com)

[LinkedIn](https://www.linkedin.com/in/kabir-chaturvedi)

[GitHub](https://github.com/kabirchaturvedi)
