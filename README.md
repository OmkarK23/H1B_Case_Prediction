#H1B Visa Case Prediction (IS-734 Project)

This project focuses on analyzing historical H1B visa data to predict whether applications will be approved or denied. Using a dataset obtained from Kaggle, the study explores patterns and builds predictive models to better understand the factors influencing visa decisions.

#Objective

The primary goal is to create a machine learning model that classifies H1B visa applications as either Certified or Denied. Additionally, the project aims to uncover the most significant features that impact these outcomes.

#Dataset
Source: Kaggle H1B Visa Dataset
Number of Records: Approximately 50,000
Time Range: 2010–2020
Key Attributes: Employer Name, Job Title, Full-Time Status, Wage, Year, Worksite, Case Status

#Data Preprocessing
Addressed missing values through forward filling and removal of incomplete rows
Eliminated unnecessary columns such as Unnamed: 0, longitude, and latitude
Standardized and cleaned feature formats for consistency
Reset the DataFrame index after preprocessing

#Exploratory Data Analysis
Identified top employers based on application frequency
Analyzed commonly occurring job roles and work locations
Compared wage distributions between approved and denied cases

#Machine Learning Models (Planned/To Be Completed)
Logistic Regression
Random Forest and/or Support Vector Machine (SVM)
Performance evaluation using Accuracy and ROC-AUC scores

#Visualizations
Confusion Matrix
ROC Curve
Feature importance plots (if applicable)

#Key Findings
Salary levels and job roles significantly influence visa decisions
Certain employers and geographic locations show higher approval rates

#Future Enhancements
Incorporate more recent datasets for improved relevance
Experiment with advanced ensemble models such as XGBoost and LightGBM
Use interpretability techniques like SHAP to better explain model decisions

#Team Members
Pranit Patil
Omkar Kalekar
Yash Soni
Siddhesh Tajanpure
Rushali Shreedhar

#License
This project is intended solely for academic and educational use.
