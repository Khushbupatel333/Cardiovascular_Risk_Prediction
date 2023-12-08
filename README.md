# Cardiovascular_Risk_Prediction
# Problem Statement:-
A group of condition affecting the heart and blood vessels that known as Cardiovascular disease.They consists of heart disease which affects the blood vessels that supply the heart muscle.The issues of coronary heart disease is significant public health concern and early prediction of CHD risk is crucial fro everyone.We have to build the classification model to predict the 10 years risk of CHD for patients.
# Variables Description:-
- age : age of clients

- education : level of education from 1 to 4

- Sex : male or female('F','M')

- Is_smoking : weather or not the patient smoke(Yes or No)

- Cigsperday : the number of cigarette

- BPMeds : weather the patient was on blood pressure

- Prevelent_stroke : weather or not patient had previously stroke

- Prevelent_hyp : weather or not patient was hypertensive

- Diabetes : weather or not patient had diabetes

- Tot_chol : Total cholestrol level

- Sys_BP : Systolic blood pressure

- Dia_BP : Diastolic blood pressure

- BMI : Body Mass Index

- Heart_Rate : Heart rate

- Glucose : glucose level

- TenYear_CHD : (binary: 1-Yes,0-No)
# Approach:-
# Data Prepration:-
- Checked null values in the dataset using isnull() and then handled them.

- Divided the whole dataset in two categories-Categorical and Numerical for visualization.

- Checked out the outliers in the data and handled them using clipping method.

# Feature Enginnering:-
- Checked the multicollinearity using heatmap and then variance inflation factor to reduce it.

- Used the One Hot Encoding method to get the dummies of the education column and label encoding for Sex and Is_smoking.

- Before the model implitation scaled the data using the MinMaxScaler().
# Used Models:-
- KNN algorithm

- Support Vector Machine

- LOgistic Regression

- Decision Tree

- Hyperparameter tunning on Random Forest

- Hyperparameter tunning on XGBoost

# Conclusion:-
- When devloping the machine learning model it is generally reccomended that track multiple metrics because each one is highlights the distict aspects.So,we are focusing on Recall and F1 score.

-  our highest F1 score is 0.914% came from XGBoost algorithm.

-Random forest classifier and KNN also provided the F1 score of 0.898 and 0.890 repectively.




-  R


