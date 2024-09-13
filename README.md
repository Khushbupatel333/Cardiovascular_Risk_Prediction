# Cardiovascular Risk Prediction: Machine Learning
![coronary](https://github.com/user-attachments/assets/042ea305-215b-458b-8fd6-67868f9fd1a7)

# Problem Statement:-
A group of conditions affecting the heart and blood vessels that known as Cardiovascular disease. They consist of heart disease which affects the blood vessels that supply the heart muscle. The issue of coronary heart disease is a significant public health concern and early prediction of CHD risk is crucial for everyone.We have to build the classification model to predict the 10-year risk of CHD for patients.
# Variables Description:-
- age : age of clients

- education: level of education from 1 to 4

- Sex : male or female('F','M')

- Is_smoking : whether or not the patient smoke(Yes or No)

- Cigsperday : the number of cigarettes

- BPMeds : whether the patient was on blood pressure

- Prevelent_stroke : whether or not the patient had a previous stroke

- Prevelent_hyp: weather or not the patient was hypertensive

- Diabetes : weather or not the patient has diabetes

- Tot_chol: Total cholesterol level

- Sys_BP : Systolic blood pressure

- Dia_BP : Diastolic blood pressure

- BMI : Body Mass Index

- Heart_Rate : Heart rate

- Glucose : glucose level

- TenYear_CHD : (binary: 1-Yes,0-No)
# Approach:-
# Data Preparation:-
- Checked null values in the dataset using isnull() and then handled them.

- Divided the whole dataset into two categories-Categorical and Numerical for visualization.

- Checked out the outliers in the data and handled them using the clipping method.

# Feature Engineering:-
- Checked the multicollinearity using heatmap and then variance inflation factor to reduce it.

- Used the One Hot Encoding method to get the dummies of the education column and label encoding for Sex and Is_smoking.

- Before the model implication the data using the MinMaxScaler().
# Used Models:-
- KNN algorithm

- Support Vector Machine

- Logistic Regression

- Decision Tree

- Hyperparameter tuning on Random Forest

- Hyperparameter tuning on XGBoost

# Conclusion:-

- When developing the machine learning model it is generally recommended to track multiple metrics because each one highlights the distinct aspects.So, we are focusing on Recall and F1 score.

- our highest F1 score is 0.914% came from the XGBoost algorithm.

- Random forest classifier and KNN also provided the F1 score of 0.898 and 0.890 respectively.




