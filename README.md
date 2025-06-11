Diabetes Dataset EDA

This project performs exploratory data analysis on the Pima Indians Diabetes dataset. The goal is to identify patterns and relationships between health metrics and the likelihood of having diabetes.

Dataset Summary

The dataset contains information on female patients aged 21 and above. Each row represents one patient with the following features

Pregnancies
Glucose
BloodPressure
SkinThickness
Insulin
BMI
DiabetesPedigreeFunction
Age
Outcome

The target variable Outcome indicates whether the patient has diabetes or not

Data Cleaning

Missing values were handled by replacing zeroes in Glucose BloodPressure SkinThickness Insulin and BMI with NaN and then imputing them using median values

EDA Summary

Histograms showed that Glucose and BMI are right skewed with most patients having moderate values
Glucose BMI and Age were notably higher in patients with diabetes
Boxplots confirmed that patients with diabetes tend to have higher values in these features
The correlation matrix showed the strongest positive correlation with diabetes is Glucose followed by BMI and Age
SkinThickness and BMI had a strong internal correlation indicating their shared relationship with body fat

Conclusion

Glucose BMI Age and Pregnancy history are strong indicators of diabetes in this dataset. This analysis helps identify important features for predictive modeling and health risk profiling