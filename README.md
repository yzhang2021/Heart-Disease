# Heart-Disease
## Background
Heart disease has become one of the leading causes of morbidity and mortality in the world. There are approximately 610,000 people die of heart disease in the U.S. and cost  $219 billion each year. They can also lead to serious illness, disability and lower quality of life.
At HCO (healthcare organization) level, heart disease contributes a large portion of inpatient and ER visits every year and readmission, which inccur a great 
## Objectives
The goal of the analysis is to predict heart disease 
## Dataset
The dataset contains 303 rows and 14 columns:

13 Predictors:

age. The age of the patient.
sex. The gender of the patient. (1 = male, 0 = female).
cp. Type of chest pain. (1 = typical angina, 2 = atypical angina, 3 = non — anginal pain, 4 = asymptotic).
trestbps. Resting blood pressure in mmHg.
chol. Serum Cholestero in mg/dl.
fbs. Fasting Blood Sugar. (1 = fasting blood sugar is more than 120mg/dl, 0 = otherwise).
restecg. Resting ElectroCardioGraphic results (0 = normal, 1 = ST-T wave abnormality, 2 = left ventricular hyperthrophy).
thalach. Max heart rate achieved.
exang. Exercise induced angina (1 = yes, 0 = no).
oldpeak. ST depression induced by exercise relative to rest.
slope. Peak exercise ST segment (1 = upsloping, 2 = flat, 3 = downsloping).
ca. Number of major vessels (0–3) colored by flourosopy.
thal. Thalassemia (3 = normal, 6 = fixed defect, 7 = reversible defect).
	
Target:

num. Diagnosis of heart disease (0 = absence, 1, 2, 3, 4 = present).
## Analysis/findings
![image](https://user-images.githubusercontent.com/77829409/115139384-80f89000-9fe6-11eb-80ed-ab13ad9b9452.png)
![image](https://user-images.githubusercontent.com/77829409/115139393-8e157f00-9fe6-11eb-8c16-f18b4b972d6a.png)
![image](https://user-images.githubusercontent.com/77829409/115139399-92419c80-9fe6-11eb-8a83-ed042ada2c0d.png)
![image](https://user-images.githubusercontent.com/77829409/115139404-953c8d00-9fe6-11eb-9ae1-3967bd4571db.png)
![image](https://user-images.githubusercontent.com/77829409/115139408-9968aa80-9fe6-11eb-9a64-7900a5aeacda.png)
![image](https://user-images.githubusercontent.com/77829409/115139412-9e2d5e80-9fe6-11eb-9c99-518bcf9028f4.png)
![image](https://user-images.githubusercontent.com/77829409/115139415-a1c0e580-9fe6-11eb-9ec7-6eb0200b960c.png)
![image](https://user-images.githubusercontent.com/77829409/115139420-a71e3000-9fe6-11eb-8377-656694765ad3.png)
![image](https://user-images.githubusercontent.com/77829409/115139422-ab4a4d80-9fe6-11eb-8743-6c2808152673.png)
![image](https://user-images.githubusercontent.com/77829409/115139426-adaca780-9fe6-11eb-82c1-b96d0820f5e7.png)

The average age in disease group is higher and most ofthe cases occur in 55-65 age group. 
The average resting BP is higher in disease group. 
In disease group, ST depression induced by exercise is larger.
Heart disease occur more in males.
For chest pain (1: typical angina, 2: atypical angina, 3: nonanginal pain 4: asymptomatic), most of heart disease cases occur in asymptomatic group.
The group with abnormality with ST-T or left ventricular hypertrophy has more heart disease cases.
peoople who have angina after exercise are more likely to have heart disease
People who have flat or down-sloping ST segment after treatmill stress test are more likely to have heart disease.
There are more heart disease cases among people who have fixed or reversable defect for Thalassemia
## Machine Learning Models
Different machine learning models including KNN, Logistic Regression, Random Forest and XGBoosting were built and compared




