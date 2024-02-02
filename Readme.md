# **Heart Failure Prediction**

### [Heart Failure Prediction Dataset (kaggle.com)](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction/data)

### **Context**

Cardiovascular diseases (CVDs) are the number 1 cause of death globally, taking an estimated 17.9 million lives each year, which accounts for 31% of all deaths worldwide. Four out of 5CVD deaths are due to heart attacks and strokes, and one-third of these deaths occur prematurely in people under 70 years of age. Heart failure is a common event caused by CVDs and this dataset contains 11 features that can be used to predict a possible heart disease.

People with cardiovascular disease or who are at high cardiovascular risk (due to the presence of one or more risk factors such as hypertension, diabetes, hyperlipidaemia or already established disease) need early detection and management wherein a machine learning model can be of great help.

### **Attribute Information**

1.  Age: age of the patient \[years\]
2.  Sex: sex of the patient \[M: Male, F: Female\]
3.  ChestPainType: chest pain type \[TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic\]
4.  RestingBP: resting blood pressure \[mm Hg\]
5.  Cholesterol: serum cholesterol \[mm/dl\]
6.  FastingBS: fasting blood sugar \[1: if FastingBS > 120 mg/dl, 0: otherwise\]
7.  RestingECG: resting electrocardiogram results \[Normal: Normal, ST: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), LVH: showing probable or definite left ventricular hypertrophy by Estes' criteria\]
8.  MaxHR: maximum heart rate achieved \[Numeric value between 60 and 202\]
9.  ExerciseAngina: exercise-induced angina \[Y: Yes, N: No\]
10. Oldpeak: oldpeak = ST \[Numeric value measured in depression\]
11. ST_Slope: the slope of the peak exercise ST segment \[Up: upsloping, Flat: flat, Down: downsloping\]
12. HeartDisease: output class \[1: heart disease, 0: Normal\]

### **Source**

This dataset was created by combining different datasets already available independently but not combined before. In this dataset, 5 heart datasets are combined over 11 common features which makes it the largest heart disease dataset available so far for research purposes. The five datasets used for its curation are:

- Cleveland: 303 observations
- Hungarian: 294 observations
- Switzerland: 123 observations
- Long Beach VA: 200 observations
- Stalog (Heart) Data Set: 270 observations

Total: 1190 observations  
Duplicated: 272 observations

`Final dataset: 918 observations`

# **Appendex**

### **Typical angina chest pain**

Is a type of chest pain caused by reduced blood flow to the heart. It usually occurs during physical or emotional stress and goes away with rest or medication. It may feel like pressure, squeezing, tightness, or heaviness in the chest, and may also affect the arms, neck, jaw, shoulder, or back. [It is a symptom of coronary artery disease, which is a condition where the arteries that supply blood to the heart become narrowed or blocked by plaque1](https://www.msn.com/en-us/health/condition/Angina/hp-Angina?source=conditioncdx)[2](https://www.mayoclinic.org/diseases-conditions/angina/symptoms-causes/syc-20369373). [Typical angina chest pain is also known as stable angina, because it follows a predictable pattern and does not indicate an immediate risk of a heart attack3](https://www.heart.org/en/health-topics/heart-attack/angina-chest-pain). However, it is still a serious condition that requires medical attention and lifestyle changes to prevent further complications. [If you have chest pain that is new, severe, or lasts longer than usual, you should seek emergency care, as it may be a sign of unstable angina or a heart attack3](https://www.heart.org/en/health-topics/heart-attack/angina-chest-pain).

### **Atypical angina**

Is a form of chest pain that does not fit the typical presentation of squeezing, pressure, heaviness, or tightness. It may be associated with symptoms like fainting, nausea, generalized weakness, fatigue, sleep disturbances, or shortness of breath. [It is more often observed in older individuals, individuals with diabetes, or women1](https://my.clevelandclinic.org/health/symptoms/24935-atypical-chest-pain).

[Atypical angina may be caused by various factors, such as stress, acid reflux, lung problems, or inflammation of the chest wall2](https://www.belmarrahealth.com/atypical-angina-causes-symptoms-treatment/). [It may also be a sign of a serious heart condition, such as acute coronary syndrome, pericarditis, myocarditis, or aortic dissection1](https://my.clevelandclinic.org/health/symptoms/24935-atypical-chest-pain)[2](https://www.belmarrahealth.com/atypical-angina-causes-symptoms-treatment/).

If you experience atypical chest pain, you should always contact a healthcare provider. They can diagnose the cause of your pain and provide appropriate treatment. [Depending on the cause, treatment may include medication, lifestyle changes, surgery, or other interventions1](https://my.clevelandclinic.org/health/symptoms/24935-atypical-chest-pain)[2](https://www.belmarrahealth.com/atypical-angina-causes-symptoms-treatment/)

### **Non-anginal pain**

Is chest pain that is not caused by heart disease. It may feel like pressure, squeezing, or tightness behind the breast bone, and it may spread to the neck, back, or left arm. [Non-anginal pain can have many possible causes, such as gastroesophageal reflux disease (GERD), musculoskeletal problems, or respiratory conditions1](https://www.medicalnewstoday.com/articles/nonanginal-chest-pain)[2](https://my.clevelandclinic.org/health/diseases/15851-gerd-non-cardiac-chest-pain)[3](https://gi.org/topics/non-cardiac-chest-pain/). If you have chest pain, you should consult a doctor to rule out any serious conditions.

### **Electrocardiogram (ECG)**

ST-T wave abnormality is a term that describes changes in the ST segment and/or T wave of the electrocardiogram (ECG) that may indicate cardiac problems. The ST segment is the flat part of the ECG between the end of the QRS complex and the beginning of the T wave, and the T wave is the peak that follows the QRS complex. [Normally, the ST segment is at the same level as the baseline (isoelectric line), and the T wave is upright and symmetrical1](https://www.healio.com/cardiology/learn-the-heart/ecg-review/ecg-interpretation-tutorial/68-causes-of-t-wave-st-segment-abnormalities).

![T wave](https://www.bing.com/th?id=OSK.d79e8d74e9bba3f49f63b422858d1bf1&pid=cdx&w=320&h=189&c=7&rs=1)

[There are many possible causes of ST-T wave abnormality, such as ischemia (reduced blood flow to the heart muscle), infarction (death of heart muscle cells), electrolyte imbalance, medication effect, cardiac arrhythmia, myocarditis (inflammation of the heart muscle), pericarditis (inflammation of the sac around the heart), pulmonary embolism (blood clot in the lung), and others1](https://www.healio.com/cardiology/learn-the-heart/ecg-review/ecg-interpretation-tutorial/68-causes-of-t-wave-st-segment-abnormalities)[2](https://www.uptodate.com/contents/ecg-tutorial-st-and-t-wave-changes). Some of the types of ST-T wave abnormality are:

- [ST segment elevation: when the ST segment is above the baseline, it may indicate acute myocardial infarction (heart attack), especially if it is present in two or more contiguous leads and accompanied by chest pain2](https://www.uptodate.com/contents/ecg-tutorial-st-and-t-wave-changes)[3](https://ecgwaves.com/topic/ecg-myocardial-ischemia-ischemic-changes-st-segment-t-wave/).
- [ST segment depression: when the ST segment is below the baseline, it may indicate myocardial ischemia, especially if it is horizontal or downsloping and present in two or more contiguous leads2](https://www.uptodate.com/contents/ecg-tutorial-st-and-t-wave-changes)[3](https://ecgwaves.com/topic/ecg-myocardial-ischemia-ischemic-changes-st-segment-t-wave/). [It may also be seen in other conditions, such as ventricular hypertrophy, bundle branch block, or digoxin effect1](https://www.healio.com/cardiology/learn-the-heart/ecg-review/ecg-interpretation-tutorial/68-causes-of-t-wave-st-segment-abnormalities).
- [T wave inversion: when the T wave is inverted (negative), it may indicate myocardial ischemia or infarction, especially if it is deep and symmetric2](https://www.uptodate.com/contents/ecg-tutorial-st-and-t-wave-changes)[3](https://ecgwaves.com/topic/ecg-myocardial-ischemia-ischemic-changes-st-segment-t-wave/). [It may also be seen in other conditions, such as ventricular hypertrophy, bundle branch block, or pulmonary embolism1](https://www.healio.com/cardiology/learn-the-heart/ecg-review/ecg-interpretation-tutorial/68-causes-of-t-wave-st-segment-abnormalities).
- [T wave flattening: when the T wave is flattened (low amplitude), it may indicate myocardial ischemia or electrolyte imbalance, such as hypokalemia (low potassium level)1](https://www.healio.com/cardiology/learn-the-heart/ecg-review/ecg-interpretation-tutorial/68-causes-of-t-wave-st-segment-abnormalities)[2](https://www.uptodate.com/contents/ecg-tutorial-st-and-t-wave-changes).
- [T wave peaking: when the T wave is peaked (high amplitude), it may indicate hyperkalemia (high potassium level) or acute myocardial infarction1](https://www.healio.com/cardiology/learn-the-heart/ecg-review/ecg-interpretation-tutorial/68-causes-of-t-wave-st-segment-abnormalities)[2](https://www.uptodate.com/contents/ecg-tutorial-st-and-t-wave-changes).
- [Biphasic T wave: when the T wave has two phases, positive and negative, it may indicate myocardial ischemia or infarction, especially if the negative phase is prominent2](https://www.uptodate.com/contents/ecg-tutorial-st-and-t-wave-changes)[3](https://ecgwaves.com/topic/ecg-myocardial-ischemia-ischemic-changes-st-segment-t-wave/). [It may also be seen in other conditions, such as ventricular hypertrophy, bundle branch block, or pericarditis1](https://www.healio.com/cardiology/learn-the-heart/ecg-review/ecg-interpretation-tutorial/68-causes-of-t-wave-st-segment-abnormalities).

The interpretation of ST-T wave abnormality depends on the clinical context, the presence of symptoms, and the comparison with previous ECGs. Therefore, it is important to consult a doctor if you have any concerns about your ECG results.
