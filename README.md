# HeartAttack
A project aimed at predicting a heart event.
The various factors by which the forecast will occur are described in the different columns in the Data Set.
##The information represented in the columns:

#Sex: 1 = male; 0 = female. 
#Cp: chest pain type; Value 1- typical angina; Value 2- atypical angina; Value 3- non-anginal pain; Value 4- asymptomatic.
#Trestbps: resting blood pressure; normal-120; high-above 140; low-under 90.
#Chol: serum cholestoral in mg/dl; noraml-if age is not more than 19-at most 170 mg/dL, else-125–200 mg/dL.
#Fbs: fasting blood sugar > 120 mg/dl: 1 = true; 0 = false.
#Restecg: resting electrocardiographic results; Value 0-normal; Value 1-abnormality; Value 2- probable or left ventricular hypertrophy.
#Thalach: maximum heart rate achieved.
#Exang: exercise induced angina; 1 = yes; 0 = no.
#Oldpeak: ST depression induced by exercise relative to rest.
#Slope:  slope: the slope of the peak exercise ST segment; Value 1- upsloping; Value 2- flat; Value 3- downsloping.
#Ca: number of major vessels (0-3) colored by flourosopy.
#Thal: 3 = normal; 6 = fixed defect; 7 = reversable defect.
#Num: Heart disease status: the predict column; 0- no disease; 1- disease.

The prediction is done using two models:
The first logistic regression and the second random forest.
