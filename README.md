# Heart-Disease-Prediction-using-Naive-Bayes-Classifier
Implementation of naive bayes classifier in detecting the presence of heart disease using the records of previous patients.

Naive bayes classifier implemented from scratch without the use of any standard library and evaluation on the dataset available from UCI. Comparison of this model is made with Gaussian Naive Bayes Classifier of sklearn library. I have used 5 random partitions of training and testing dataset to evaluate the implementation and results are given for each partition.

Dataset for evaluating Naïve Bayes classifier: Heart Disease Data Set


heartdisease.txt is the dataset where 14 different attributes are taken for every patient.
The following 14 attributes were taken: age (in years), sex (male or female), cp (chest pain type), trestbps (resting blood pressure in mm Hg on admission to the hospital), chol (serum cholesterol in mg/dl) , restecg (resting electrocardiographic results), thalach (maximum heart rate achived), exang (exercise induced angina), oldpeak (ST depression induced by exercise relative to rest ), slope(the slope of the peak exercise ST segment), ca(number of major vessels (0-3) colored by flourosopy ) , thal( normal, fixed defect, reversable defect ), num (the predicted attribute) .

1.age: The person's age in years

2.sex: The person's sex (1 = male, 0 = female)

3.cp: The chest pain experienced (Value 1: typical angina, Value 2: atypical angina, Value 3: non-anginal pain, Value 4: asymptomatic)

4.trestbps: The person's resting blood pressure (mm Hg on admission to the hospital)

5.chol: The person's cholesterol measurement in mg/dl

6.fbs: The person's fasting blood sugar (> 120 mg/dl, 1 = true; 0 = false)

7.restecg: Resting electrocardiographic measurement (0 = normal, 1 = having ST-T wave abnormality, 2 = showing probable or definite left ventricular hypertrophy by Estes' criteria)

8.thalach: The person's maximum heart rate achieved

9.exang: Exercise induced angina (1 = yes; 0 = no)

10.oldpeak: ST depression induced by exercise relative to rest ('ST' relates to positions on the ECG plot. See more here)

11.slope: the slope of the peak exercise ST segment (Value 1: upsloping, Value 2: flat, Value 3: downsloping)

12.ca: The number of major vessels (0-3)

13.thal: A blood disorder called thalassemia (3 = normal; 6 = fixed defect; 7 = reversable defect)

14.target: Heart disease (0 = no, 1 = yes)

Heart disease risk factors to the following: high cholesterol, high blood pressure, diabetes, weight, family history and smoking .
According to another source , the major factors that can't be changed are: increasing age, male gender and heredity.
Note that thalassemia, one of the variables in this dataset, is heredity.
Major factors that can be modified are: Smoking, high cholesterol, high blood pressure, physical inactivity, and being overweight and having diabetes.
Other factors include stress, alcohol and poor diet/nutrition.

As the calssifier is taking random partitions for 5 different times, random results would be predicted with average accuracy being around 50.00 %.
