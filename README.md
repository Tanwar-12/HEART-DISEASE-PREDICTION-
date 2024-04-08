# **𝐇𝐞𝐚𝐫𝐭 𝐃𝐢𝐬𝐞𝐚𝐬𝐞 𝐏𝐫𝐞𝐝𝐢𝐜𝐭𝐢𝐨𝐧**

<div align="center">
  <img src="https://github.com/Tanwar-12/Heart-Disease-Prediction/assets/110081008/6fbdce0d-e31e-4b55-9daf-fd7f77193483" alt="Description of the image">
</div>


## **𝐁𝐔𝐒𝐈𝐍𝐄𝐒𝐒 𝐂𝐀𝐒𝐄 :**
**BASE ON GIVEN FEATURE AND MEASUREMENT PREDICT WHETHER PATIENT WILL HAVE HEART DISEASE OR NOT.**

## **𝐓𝐀𝐒𝐊**
**BINARY CLASSIFICATION TASK**


### **𝐀𝐁𝐎𝐔𝐓 𝐓𝐇𝐄 𝐏𝐑𝐎𝐉𝐄𝐂𝐓:**
Heart disease remains one of the leading causes of mortality globally, emphasizing the critical need for early detection and intervention. With advancements in technology and data analytics, predictive modeling techniques offer a promising avenue for identifying individuals at risk of heart disease, enabling timely preventive measures and personalized healthcare interventions.

##  𝐃𝐎𝐌𝐀𝐈𝐍 𝐀𝐍𝐀𝐋𝐘𝐒𝐈𝐒:
**TARGET COLUMN = HEART DISEASE PRESENT**
**In this project we are going to analyze that how other feature of dataset affecting heart disease.**

#### 1.PATIENT ID: 
Id of particular patient, Id is used to identify a patient, this is a unique column so that its not affect to heart disease

#### 2.SLOPE OF PEAK EXERCISE ST SEGMENT: 
While a high ST depression is considered normal & healthy. The “ slope ” hue, refers to the peak exercise ST segment, with values: 1: upsloping, 2: flat, 3: down-sloping). Both positive & negative heart disease patients exhibit equal distributions of the 3 slope categories.

#### 3.THAL:
A blood disorder called thalassemia,[normal, reversible defect, fixed defect]

#### 4.RESTING BLOOD PRESSURE: 
blood pressure tells a lot about your general health. High blood pressure or hypertension can lead to several heart related issues and other medical conditions. Uncontrolled high blood pressure can lead to stroke.

#### 5.CHEST PAIN TYPE:
Most of the chest pain causes are not dangerous to health, but some are serious, while the least cases are life-threatening.[TA: typical angina(1), ATA: Atypical angina(2), NAP: non-anginal pain(3), ASY: asymptomatic (4) ]

#### 6.NUM OF MAJOR VESSELS: 
Major Blood Vessels of the Heart: Blood exits the right ventricle through the pulmonary trunk artery. Approximately two inches superior to the base of the heart, this vessel branches into the left and right pulmonary arteries, which transport blood into the lungs.[number of major vessels: 0 to 3]

#### 7.FASTING BLOOD SUGAR: 
Your Fasting blood sugar level of 120 is a High Fasting blood sugar level. If your Fasting blood sugar is in between 74 mg/dL and 99 mg/dL, then you need not worry as 74-99 mg/dL is the normal range for Fasting blood sugar. But if your Fasting blood sugar is lesser or greater than the above values, then there may be some problem in your body.
(fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)

#### 8.RESTING EKG/ECG RESULT: 
The electrocardiogram (ECG or EKG) is a test that measures the heart’s electrical activity, and a resting ECG is administered when the patient is at rest. It involves noninvasive recording with adhesive skin electrodes placed on specially prepared spots on the skin, and it plots out the heart's activity on a graph. It is used to determine the health of the heart and circulatory system and to help diagnose issues with associated body systems.[0: normal, 1:having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), 2:showing probable or definite left ventricular hypertrophy by Estes’ criteria]

#### 9.SERUM CHOLESTEROL:  
A person’s serum cholesterol level represents the amount of total cholesterol in their blood. A person’s serum cholesterol level comprises the amount of high-density lipoprotein (HDL), low-density lipoprotein (LDL), and triglycerides in the blood. Triglycerides are a type of fat bundled with cholesterol.

#### 10. oldpeak_eq_st_depression: 
oldpeak = ST depression induced by exercise relative to rest, a measure of abnormality in electrocardiograms

#### 11.SEX:
sex (1 = male; 0 = female)

#### 12.AGE: 
age in years


#### 13.MAX HEART RATE: 
It has been shown that an increase in heart rate by 10 beats per minute was associated with an increase in the risk of cardiac death by at least 20%, and this increase in the risk is similar to the one observed with an increase in systolic blood pressure by 10 mm Hg.[Average heart rate: 60 to 100 bpm]

#### 14.EXERCISE INDUCED ANGINA:
Angina is chest pain or discomfort caused when your heart muscle doesn't get enough oxygen-rich blood.[0: no, 1: yes]

#### 15.HEART DISEASE PRESENT:
[0: no heart disease present, 1: heart disease present]


# 𝐄𝐗𝐏𝐋𝐎𝐑𝐀𝐓𝐎𝐑𝐘 𝐃𝐀𝐓𝐀 𝐀𝐍𝐀𝐋𝐘𝐒𝐈𝐒:
## ANALYSIS ON CATEGORICAL VERIABLE WITH RESPECT TO TARGET VERIABLE(HEART DISEASE)

![image](https://user-images.githubusercontent.com/101791322/180658181-3b9d8548-20ed-4262-bc01-d6ff34327955.png)

### OBSERVATION:

#### 1.IMPACT OF SOP TO HEART DISEASE:
* In this table clearly seen the slope of peak st segment is upsloping the chance of heart disease is less than other.
* If slop pf peak is flat the chance of heart disease in more than upsloping
* downslope st segment patient is also chance to get heart diseaase
* with the follwing observation we can say that slope of peak st segment is fullt impact to heart disease

#### 2.IMPACT OF THAL TO HEART DISEASE:
* Normal blood disorder patient has less chance of heart disease than other thal
* reversible defect blood disorder has more chance of heart disease and fixed defect blood disorder has 50-50 chance of heart disease

#### 3.IMPACT OF CPT TO HEART DISEASE:
* if the patient have asymtomatic(4) chest paint the chance of heart disease is more high
* non-anginal pain(3),typical angina(1), Atypical angina(2) chest pain has less chances of heart disease.
* but all chest pain types are impacted to heart disease.

#### 4.IMPACT OF FASTING BLOOD SUGAR TO HEART DISEASE:
* If fasting blood suagar is less than 120mg/dl the chance of heart disease is high.
* fasting blood sugar is greter than 120mg/dl the chace of heart disease is slightly less.


#### 5.IMPACT OF SEX TO HEART DISEASE:
* Male patient has more chance of heart disease than female


#### 6.IMPACT OF MAJOR VESSELS TO HEART DISEASE:
* If the major vessels is zero the chance of heart disease is less but zero major vessels are also chance of heart disease
* 1,2, and 3 major vessels are more(high) chance of heart disease

#### 7.IMPACT OF EKG RESULT TO HEART DISEASE:
* If the ekg/ecg result is normal(0) the chance of heart disease is less.
* If ekg/ecg result is 1 the 100% patient has heart disease
* 2 ekg/ecg result is 50-50% chance of heart disease

#### 8.IMPACT OF EXERCISE INDUCED ANGINA:
* If the patient has no chest pain the chance of heart disease is less 
* If patient has chest pain the chance of heart disease is more


## ANALYSIS ON NUMERICAL VERIABLE WITH RESPECT TO TARGET VERIBLE (HEART DISEASE)

![image](https://user-images.githubusercontent.com/101791322/180658294-6a2e0284-c222-4a77-a628-4649e93a6073.png)

### OBSERVATION:
#### 1.IMPACT OF RESTING BP TO HEART DISEASE:
* If the blood pressure range between 110 to 150 the chance of heart disease is more 
* If resting blood pressure is low the chance of heart disease is slightly less

#### 2.IMPACT OF SERUM CHOLESTREOL TO HEART DISEASE:
* If serum cholestreol is less than 350 the heart disease chance is 50-50 percent.
* serum cholestreol is more than 350 thier is no chance of heart disease

#### 3.IMPACT OF OLD PEAK DEPRESSION TO HEART DISEASE:
* If old peak depression is less the chance of heart disease is less 
* old peak depression is more than 1 the chance of heart disease is more

#### 4.IMAPCT OF AGE TO HEART DISEASE:
* At the age of 60 the more chance of heart disease and age range between 40 to 70 heart disease chance is 50-50 percent
* If age is less than 30 their is no chance of heart disease

#### 5.IMAPCT OF MAX HEART RATE TO HEART DISEASE:
* If the heart rate is less than 140 the chance of heart disease is more
* Above 140 heart rate chance of heart disease is 50-50 percent.
* If the heart rate is more than 180 their is no chance of heart disease.

  ## 𝐃𝐀𝐓𝐀 𝐏𝐑𝐄𝐏𝐑𝐎𝐂𝐄𝐒𝐒𝐈𝐍𝐆 / 𝐅𝐄𝐀𝐓𝐔𝐑𝐄 𝐄𝐍𝐆𝐈𝐍𝐄𝐄𝐑𝐈𝐍𝐆:
  
  **1.CHECK MISSING VALUE**
  
  **2.CATEGORICAL DATA CONVERSION**
  
* MANUAL ENCODING
**Manual encoding is best technique to handle categorical data with the help of map function**

 **3.OUTLIER HANDLING**

  **CHECKING DISTRIBUTION AFTER HANDLE OUTLIER**

 ![image](https://github.com/Tanwar-12/Heart-Disease-Prediction/assets/110081008/e36170d5-03dd-428b-b49f-1ce4dc962059)



## 𝐅𝐄𝐀𝐓𝐔𝐑𝐄 𝐒𝐂𝐀𝐋𝐈𝐍𝐆:
**STANDARD SCALING**

* Standard scaling is used because of features are mesure in different units as well as some feature are followed normal distribution
* Standard scaling range : -3 to +3

## 𝐅𝐄𝐀𝐓𝐔𝐑𝐄 𝐒𝐄𝐋𝐄𝐂𝐓𝐈𝐎𝐍 :

1.DROP UNIQUE AND CONSTANT COULUMNS

2.CHECKING CORRELATION

3.CHECKING DUPLICATES

## 𝐌𝐎𝐃𝐄𝐋 𝐂𝐑𝐄𝐀𝐓𝐈𝐎𝐍:
###  𝐀𝐈𝐌:
In heart disease case recall metrix is more important so we need more focus to improve recall score
Create sweetspot model (Low bias & Low variance)
**HERE WE WILL BE EXPERIMENTING WITH FOUR ALGORITHMS**:

* Logistic regression
* KNeighborsClassifier
* RandomForestClassifier
* XGBClassifier

## 𝐂𝐎𝐍𝐂𝐋𝐔𝐒𝐈𝐎𝐍:
* Logistic regression model is performed well on training data with 84.72% accuracy and testing data with 83.33% accuracy as well as recall score is 87.50% after apply bagging recall score 88.88%.
* KNN model is performed very well on training data with 88.19% accuracy but in testing data model accuracy and recall score is lagging
* Random forest model performed very well on training data with 100% accuracy but in testing data model is not perfomed well after applying hyperparameter tunning recall score still lagging
* XG boost model is also performed well on training data with 100% accuracy but in testing data accuracy is extrmely lagging after apply hyperparameter tunning the recall score is 87.50%
**From above all model we are select logistic regression model beacuse it is performed very well on training as well as testing data and recall score is also good.**




 

