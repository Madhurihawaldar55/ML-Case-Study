# ML-Case-Study- EDA and Building ML Model for Predicting Diabetes
About Data :

For my ML Case Study Project I have choosen the dataset of DIABETES from PIMA INDIAN DIABETES DATABASE
The Diabetes Dataset contains information about individuals diagnosed with diabetes, including demographic attributes, medical history, and clinical measurements. This dataset serves as a valuable resource for studying diabetes management, risk factors, and predictive modeling for disease outcomes.
Diabetes is a disease that occurs when your blood glucose, also called blood sugar, is too high.The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset.
In particular all patients here are females at least 21 years old of Pima Indiann Heritage. We will explore this dataset and find out factors that contribute the most for diabetes causation. We will also build a machine learning models that can help to predict whether a person is diabetic or not.
# Conclusion:
1. The number of pregnancies is high for the diabetic people.
2. The median of the Glucose level of Diabetic People is greater than the 75th Percentile of the glucose level of non-diabetic people. Therefore having a high glucose level does increase the chances of having diabetes.
3. The median of the BloodPressure of diabetic people lies close to the 75th Percentile of non-diabetic people.
4. The Median BMI of the Diabetic People is greater than the Median BMI of the Non-Diabetic people.
5. The Insulin level is more in Diabetic people compare to non diabetic people.
6. As the age increases, generally the Blood Pressure also increases
7. As the Insulin increases the Glucose level increases.
#####**Conclusion from ML model**
##### We got the best results for Logistic Regression Algorithm, the accuracy in this case is 78.3%. The Results for Random Forest(75%) and KNeighbors Classifer(75.7%) is also not bad
