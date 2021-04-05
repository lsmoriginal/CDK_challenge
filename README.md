# CDK_challenge  

This is a project that uses two tables: **Measurement** and **Medication**.  

Measurement table contains patient information such as their age, gender, race, disease progress and other health statuses(refer to Medical 101 below).  
Medication table contains the prescription of medicine given to each patient to be taken at different time period.  

# Methodology

The analysis revolves around the concept of [**Summary Statistics**](https://en.wikipedia.org/wiki/Summary_statistics).  

<br>
<hr>
<br>



## Medical 101  

### Creatinine  

Creatinine is a **waste product** produced by muscles from the breakdown of a compound called creatine. Creatinine is **removed from the body by the kidneys**, which filter almost all of it from the blood and release it into the urine. This test measures the amount of creatinine in the blood and/or urine.

Elevated creatinine level  signifies  **impaired kidney function** or kidney disease. As the kidneys become impaired for any reason, the creatinine level in the blood will rise due to poor clearance of creatinine by the kidneys. Abnormally high levels of creatinine thus warn of possible malfunction or failure of the kidneys.  
 
 ### DBP/SBP  

* Diastolic Blood Pressure  
* Systolic Blood Pressure  

Renal function in CKD patients is affected by **low or high SBP either side of 100 mm of Hg**, whereas **DBP affects renal function primarily when it is lower than 75 mm of Hg**. DBP should be given careful consideration so as not to lower it too aggressively while managing hypertension in CKD patients. 

### Glucose  

**When kidneys fail**, urea that builds up in the blood can **cause diabetes**, concludes a study published today in the Journal of Clinical Investigation. "We identified molecular mechanisms that may be responsible for increased blood glucose levels in patients with non-diabetic chronic kidney disease.  

### HGB

Hemoglobin (Hgb) is the protein in red blood cells that carries oxygen from the lungs to the cells of the body.  

When kidneys are healthy, they make a hormone called erythropoietin, or EPO.  This hormone helps the bone marrow to produce the amount of red blood cells (RBC) that the body needs to carry oxygen to vital organs. When the **kidneys are damaged**, they often **do not make enough EPO**.  As a result, the bone marrow makes too few red blood cells.

### LDL

If you have a high LDL level, this means that you have too much LDL cholesterol in your blood. This extra LDL, along with other substances, forms plaque. The plaque builds up in your arteries; this is a condition called atherosclerosis.  

In people with **chronic kidney disease (CKD)**, heart and **blood vessel disease is very common**.  


<br>
<hr>
<br>

Field | (Low, | Normal | ,High) | unit | Context  
-- | -- |-- |-- |--| --    
Creatining | 65 | 100  | 120 | micromoles/L | High is bad    
Diastolic Blood Pressure | 60 | 70 | 80 | mm Hg | High is bad
Systolic Blood Pressure | 100 | 120 | 140 | mm Hg | Both is bad  
Glucose | 4.0 | 7.8 | 11.1 | mmol/L | High is bad  
HBG | 13.5 | 15.5 | 17.5 | g/dL | Low is bad  
LDL | 100 | 120 | 130 | mg/dL | High is bad  


# Model 

The report is for the final model developed using Random Forest(decision threshold = 0.3)
 
![image info](https://github.com/lsmoriginal/CDK_challenge/blob/main/Model.PNG)
