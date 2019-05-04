# DM
Diabetes prediction using classification
PROBLEM STATEMENT:

The objective of this project is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset.



DATASET DESCRIPTION:

This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients are females at least 21 years old of Pima Indian heritage. The datasets consists of several medical predictor variables and one target variable, Outcome. Predictor variables includes the number of pregnancies the patient has had, their BMI, insulin level, age, and so on. 
There are 8 attributes which were considered for predicting the outcome, namely,
Pregnancies, Glucose, Blood Pressure, Skin Thickness, Insulin, BMI, DiabetesPedigreeFunction and age. There are a total of 768 records in this dataset. All the attributes considered are ordinal. 

EXPERIMENTAL RESULTS:
The partition of data is as following:
Training set : 70%
Test set : 30%
The accuracy obtained by using K nearest neighbours = 72.908366533864654%
The accuracy obtained by using Decision tree (using Gini Index) = 70.9956709957%
 
CONCLUSION:
In our project, we noticed that KNN performed better on our dataset. In KNN, the difference between the records were calculated using Euclidean Distance. Gini index is used for Decision tree.  
