ML-CA-1: Vehicle Crash Victim Injury Severity Prediction
This repository contains the code and an exploratory data analysis (EDA) report for a machine learning project focused on predicting the severity of injuries sustained by individuals involved in vehicle crashes. The project utilizes a dataset of over 50,000 records to build a predictive model that can be valuable for traffic safety policy, insurance risk assessment, and smart car safety system development.
📁 Repository Contents
•	ML_CA_1_Project.ipynb: A Jupyter Notebook containing all the code for data loading, preprocessing, exploratory data analysis (EDA), and the machine learning plan.
•	Raw Dataset.csv: The original dataset with 50,000 records of vehicle crash victims.
•	EDA_Report_ML_CA1.docx: A detailed report summarizing the key findings from the EDA, including visualizations and insights into the dataset's structure, missing values, and feature correlations.
•	cleaned_dataset.csv: The cleaned and preprocessed version of the dataset, with missing values handled and ready for machine learning model training.
•	data_types.png: A visualization of the data types for each column in the dataset.
•	missing_values_heatmap.png: A heatmap showing the distribution of missing values across the dataset's features.
•	correlation_heatmap.png: A heatmap displaying the Pearson correlation coefficients between the numerical features.
•	dist_year.png: A histogram visualizing the distribution of crash records by year.
•	dist_case_individual_id.png: A histogram showing the distribution of the unique individual ID values.
•	dist_age.png: A histogram with a KDE curve illustrating the age distribution of crash victims.
🎯 Project Objective
The primary goal of this project is to build a classification model that can predict the Injury Severity of a crash victim based on various factors. This is a crucial step towards understanding the conditions that lead to severe injuries and can inform data-driven decisions in road safety.
🚀 Use Case
The predictive model developed in this project can support:
•	Policy Formulation: Identifying which conditions are most associated with severe injuries to guide road safety policies.
•	Insurance Risk Assessment: Providing a data-backed approach for assessing risk factors in crash scenarios.
•	Smart Car Safety Systems: Informing the development of future safety systems in vehicles to better protect occupants.
📊 Exploratory Data Analysis (EDA)
The EDA was conducted to understand the dataset's structure, identify patterns, and prepare the data for modeling. Key findings from the EDA include:
•	Dataset Size: The raw dataset contains 50,000 records and 15 columns.
•	Missing Values: Significant missing data was observed in columns such as License State Code, Transported By, and Safety Equipment. For this analysis, rows with missing values were removed, resulting in a cleaned dataset with 32,858 rows.
•	Data Distribution:
o	The Year column is heavily skewed towards 2019, indicating that the majority of the data is from that year.
o	The Age distribution is slightly right-skewed, with the majority of victims falling between 20 and 60 years old.
o	Role Type and Victim Status show a high frequency for "Driver" and "Not Applicable" respectively, which may require careful handling during feature engineering.
•	Feature Correlation: A strong positive correlation (0.94) was found between Year and Case Vehicle ID, suggesting multicollinearity. This is an important consideration for model selection.
🤖 Machine Learning Plan
Given that the target column Injury Severity is categorical, this is a classification problem. The following machine learning algorithms are planned for application:
•	Logistic Regression
•	Decision Tree Classifier
•	Random Forest Classifier
•	K-Nearest Neighbors (KNN)
•	Support Vector Machine (SVM)
🤝 How to Contribute
This project is a work in progress. If you would like to contribute, please feel free to fork the repository and submit a pull request with your suggested improvements.
Author: Devansh Motghare 

