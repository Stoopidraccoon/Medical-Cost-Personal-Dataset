# Medical Insurance Cost Prediction

# Objective
The objective of this project is to predict individual medical insurance costs based on personal attributes such as age, gender, BMI, number of children, smoking status, and region. By applying regression models, we aim to assist insurance providers in estimating premiums more accurately.

# Dataset Overview
The dataset used for this project is the Medical Cost Personal Dataset, available on Kaggle. It contains 1,338 records and the following features:

**Feature and Description**
- age	        -  Age of the individual
- sex       	-  Gender (male or female)
- bmi       	-  Body Mass Index (weight in kg / height in m²)
- children	  -  Number of children/dependents covered
- smoker    	-  Smoking status (yes or no)
- region	    -  Residential area in the US (northeast, etc.)
- charges	    -  Medical insurance cost (target variable)

# Approach
Data Cleaning & Preprocessing

- Checked for and handled missing values.
- Encoded categorical variables 
- Exploratory Data Analysis (EDA)

Visualized distributions and relationships between features using:
Boxplots (e.g., smoker vs charges)
Line graph (Average charges by age and BMI) 

# Model Training
- Used Linear Regression as the primary model.
- Performed train-test split to evaluate generalization.

# Evaluation Metrics
- **Mean Absolute Error (MAE)**: 4181.19
- **Root Mean Squared Error (RMSE)**: 5796.28
- **R² Score**: 78.3593

# Results and Insights
Smoking status and BMI showed a strong influence on insurance charges.
- Smokers had significantly higher average charges.
- Linear Regression gave a reasonable performance, but ensemble models improved accuracy further.
