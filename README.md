#HEART DISEASE REGRESION ANALYSIS

###Overview
The purpose of this project is to anaylze health factors that may correlate with heart disease. This will be done by analyzing the factors through a series of different classification techniques. The optimality of the techniques will be evaluated by using them in order to train models to predict the likelihood of a person having heart disease.


###Background
Data will be a subset of the UCI Heart Disease dataset. This data has been fully supervised by UCI meaning that it's been fully labeled and we can trust the veracity of the labeling.
Labels
age: Age in years
sex: (1 = male; 0 = female)
cp: Chest pain type (0 = asymptomatic; 1 = atypical angina; 2 = non- anginal pain; 3 = typical angina)
trestbps: Resting blood pressure (in mm Hg on admission to the hospital) cholserum: Cholestoral in mg/dl
fbs Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
restecg: Resting electrocardiographic results (0= showing probable or definite left ventricular hypertrophy by Estes' criteria; 1 = normal; 2 = having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV))
thalach: Maximum heart rate achieved
exang: Exercise induced angina (1 = yes; 0 = no)
oldpeakST: Depression induced by exercise relative to rest
slope: The slope of the peak exercise ST segment (0 = downsloping; 1 = flat; 2 = upsloping)
ca: Number of major vessels (0-4) colored by flourosopy
thal: 1 = normal; 2 = fixed defect; 3 = reversable defect
sick: Indicates the presence of Heart disease (True = Disease; False = No disease)


### Results 
From this we can see that the (cp, exang, ca) combo is most accurate for predicting whether or not a person will have heart disease. Looking back these are the meaning for those variables
cp: Chest pain type (0 = asymptomatic; 1 = atypical angina; 2 = non-anginal pain; 3 = typical angina)
ca: Number of major vessels (0-4) colored by flourosopy
exang: Exercise induced angina (1 = yes; 0 = no)
With this in mind, we can see that these factors could be good indicators as the number of vessels exposed can show the functionality of the vessels in the heart with chest pain and exercise induced angina are also closely related with heart function.
