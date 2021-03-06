# heartdiseasepredict

This code helps us to predict the Heart disease based on the other paramters available in our datasheet.

The dataset(heart.csv) contains several parameters which are considered important during the prediction of heart disease
The parameters included are :
1.	 Age
2.	Sex (0 – female and 1 – male)
3.	cp: chest pain type
-- Value 1: typical angina
-- Value 2: atypical angina
-- Value 3: non-anginal pain
-- Value 4: asymptomatic
4.	trestbps: resting blood pressure (in mm Hg on admission to the hospital)
5.	12 chol: serum cholesterol in mg/dl
6.	 fbs: (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
7.	restecg: resting electrocardiographic results
-- Value 0: normal
-- Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
-- Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria
8.	thalach: maximum heart rate achieved
9.	exang: exercise induced angina (1 = yes; 0 = no)
10.	oldpeak = ST depression induced by exercise relative to rest
11.	slope: the slope of the peak exercise ST segment
-- Value 1: upsloping
-- Value 2: flat
-- Value 3: downsloping
12.	ca: number of major vessels (0-3) colored by flourosopy
13.	thal: 3 = normal; 6 = fixed defect; 7 = reversable defect
14.	 num: diagnosis of heart disease (angiographic disease status)
-- Value 0: < 50% diameter narrowing
-- Value 1: > 50% diameter narrowing (Predicted value)

This project is build using the following models:
1.	Support Vector Machines (SVM)
2.	K – nearest neighbor classifier (K-NN)
3.	SVM with PCA
4.	K-NN with PCA

It also contains code for plotting the confusion matrix and Accuracy for each Model.
