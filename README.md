# **Bank Marketing Classification Model 🏦📊**  

## **Overview**  
This project builds a **Bank Marketing Classification Model** to predict whether a customer will subscribe to a bank term deposit. The goal is to help banks and financial institutions identify potential customers and improve marketing strategies.  

The following classification algorithms are used in this model:  
- **Logistic Regression**  
- **Decision Tree Classifier**  
- **Random Forest Classifier**  
- **XGBoost Classifier**  
- **K-Nearest Neighbors (KNN) Classifier**  
- **Support Vector Machine (SVM) Classifier**  
- **AdaBoost Classifier**  
- **Voting Classifier**  

## **Dataset**  
The dataset used is **"train.csv"**, which contains various customer-related features such as **age, job type, marital status, education, balance, loan status, and communication details**. The dataset is preprocessed by handling missing values, encoding categorical variables, and normalizing numerical features.  

## **Project Workflow** 🚀  

### **1. Data Preprocessing**  
- Handling missing values and ensuring data consistency.  
- Encoding categorical variables for machine learning models.  
- Normalizing numerical data for better model performance.  

### **2. Exploratory Data Analysis (EDA)**  
- Understanding customer trends in bank marketing campaigns.  
- Identifying key factors influencing customer subscription.  

### **3. Feature Engineering**  
- Selecting the most important features that impact customer subscription.  
- Creating new features to improve model accuracy.  

### **4. Model Implementation**  
- Training multiple classification models to predict customer subscription.  
- Comparing model performance based on evaluation metrics.  

### **5. Model Evaluation**  
The models are evaluated using the following metrics:  
- **Accuracy Score** – Measures the percentage of correctly predicted customer subscriptions.  
- **Precision Score** – Measures the percentage of correctly predicted positive cases.  
- **Recall Score** – Measures the percentage of actual positive cases that were correctly identified.  

## **Results & Key Insights** 🔍  
- **Logistic Regression** provides a simple baseline model.  
- **Decision Tree and XGBoost capture complex decision-making patterns.**  
- **AdaBoost Classifier gives the highest accuracy**, making it the best-performing model for this dataset.  
- **KNN and SVM perform well but are sensitive to data scaling.**  
- **Voting Classifier combines multiple models to improve stability.**  

## **Technologies Used**  

- **Python**  
- **Pandas** – Data manipulation and analysis.  
- **NumPy** – Numerical computations.  
- **Scikit-learn** – Machine learning algorithms.  
- **Matplotlib & Seaborn** – Data visualization.  

## **Contribution**  

Feel free to contribute by optimizing hyperparameters, testing additional models, or improving feature selection! 😊  

## **License**  

This project is open-source under the **MIT License**.

