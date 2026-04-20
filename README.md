### EX1 Creation of Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform Preprocessing
### DATE: 20.04.2026
### AIM: 
  To Create Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform preprocessing
### PROCEDURE: 
1) Open Start -> Programs -> Accessories -> Notepad
2) Type the following training data set with the help of Notepad for Employee Table.

```
--------------
Employee Data
---------------
@relation employee-weka.filters.unsupervised.attribute.Normalize-S1.0-T0.0

@attribute name string
@attribute salary numeric
@attribute experience string
@attribute working_time numeric
@attribute working_days numeric
@attribute leaves_taken numeric

@data
shravin,80000,2year,0,0,2
rohitcj,300000,2year,0,0,2
jana,750000,2year,0,0,2
maddy,45826,2year,0,0,2

--------------
Weather Data
---------------
@relation weather

@attribute outlook {sunny, overcast, rainy}
@attribute temperature {hot, mild, cool}
@attribute humidity {high, normal}
@attribute windy {TRUE, FALSE}
@attribute play {yes, no}

@data
sunny,hot,high,FALSE,no
sunny,hot,high,TRUE,no
overcast,hot,high,FALSE,yes
rainy,mild,high,FALSE,yes
rainy,cool,normal,FALSE,yes
rainy,cool,normal,TRUE,no
overcast,cool,normal,TRUE,yes
sunny,mild,high,FALSE,no
sunny,cool,normal,FALSE,yes
rainy,mild,normal,FALSE,yes
sunny,mild,normal,TRUE,yes
overcast,mild,high,TRUE,yes
overcast,hot,normal,FALSE,yes
rainy,mild,high,TRUE,no
```
3) After that the file is saved with .arff file format.
4) Minimize the arff file and then open Start -> Programs -> weka-3-4.
5) Click on weka-3-4, then Weka dialog box is displayed on the screen.
6) In that dialog box there are four modes, click on explorer.
7) Explorer shows many options. In that click on ‘open file’ and select the arff file
8) Click on edit button which shows employee table on weka.

### OUTPUT:
<img width="1919" height="1079" alt="employee ss" src="https://github.com/user-attachments/assets/78dd8f02-da67-4458-88db-f62ad351c8a0" />
<img width="1730" height="890" alt="weather ss" src="https://github.com/user-attachments/assets/43441db9-2b07-498a-908b-b3c673f882c7" />





### PREPROCESSING
### Procedure:
#### 1) Add -> Pre-Processing Technique:
1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Add.
9) A new window is opened.
10) In that we enter attribute index, type, data format, nominal label values for Climate.
11) Click on OK.
12) Press the Apply button, then a new attribute is added to the Weather Table.
13) Save the file.
14) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:
<img width="1919" height="1079" alt="employee ss" src="https://github.com/user-attachments/assets/78dd8f02-da67-4458-88db-f62ad351c8a0" />
<img width="1730" height="890" alt="weather ss" src="https://github.com/user-attachments/assets/43441db9-2b07-498a-908b-b3c673f882c7" />
### 2) Remove -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Remove.
9) Select the attributes windy, play to Remove.
10) Click Remove button and then Save.
11) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:
<img width="1919" height="1079" alt="employee ss" src="https://github.com/user-attachments/assets/78dd8f02-da67-4458-88db-f62ad351c8a0" />
<img width="1730" height="890" alt="weather ss" src="https://github.com/user-attachments/assets/43441db9-2b07-498a-908b-b3c673f882c7" />
### Normalize -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Normalize.
9) Select the attributes temparature, humidity to Normalize.
10) Click on Apply button and then Save.
11) Click on the Edit button, it shows a new Weather Table with normalized values on Weka.

### OUTPUT:
<img width="1919" height="1079" alt="employee ss" src="https://github.com/user-attachments/assets/78dd8f02-da67-4458-88db-f62ad351c8a0" />
<img width="1730" height="890" alt="weather ss" src="https://github.com/user-attachments/assets/43441db9-2b07-498a-908b-b3c673f882c7" />
### RESULT: 
  Thus the program for generating employee and weather datasets has been developed, and preprocessing has been accomplished successfully.
