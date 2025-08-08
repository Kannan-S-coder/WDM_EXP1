### EX1 Creation of Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform Preprocessing
### DATE: 08/08/2025
### AIM: 
  To Create Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform preprocessing
### PROCEDURE: 
1) Open Start -> Programs -> Accessories -> Notepad
2) Type the following training data set with the help of Notepad for Employee Table.

```
--------------
Employee Data
---------------
@relation employee
@attribute name {x,y,z,a,b}
@attribute id numeric
@attribute salary {low,medium,high}
@attribute exp numeric
@attribute gender {male,female}
@attribute phone numeric
@data
x,101,low,2,male,250311
y,102,high,3,female,251665
z,103,medium,1,male,240238
a,104,low,5,female,200200
b,105,high,2,male,240240

--------------
Weather Data
---------------
@relation weather
@attribute outlook {sunny,rainy,overcast}
@attribute temparature numeric
@attribute humidity numeric
@attribute windy {true,false}
@attribute play {yes,no}
@data
sunny,85.0,85.0,false,no
overcast,80.0,90.0,true,no
sunny,83.0,86.0,false,yes
rainy,70.0,86.0,false,yes
rainy,68.0,80.0,false,yes
rainy,65.0,70.0,true,no
overcast,64.0,65.0,false,yes
sunny,72.0,95.0,true,no
sunny,69.0,70.0,false,yes
rainy,75.0,80.0,false,yes
```
3) After that the file is saved with .arff file format.
4) Minimize the arff file and then open Start -> Programs -> weka-3-4.
5) Click on weka-3-4, then Weka dialog box is displayed on the screen.
6) In that dialog box there are four modes, click on explorer.
7) Explorer shows many options. In that click on ‘open file’ and select the arff file
8) Click on edit button which shows employee table on weka.

### OUTPUT:
#### Employee
<img width="1918" height="1079" alt="Screenshot 2025-08-08 105308" src="https://github.com/user-attachments/assets/04599e24-37c7-4ce7-a3f1-96eebf0db975" />

#### Weather
<img width="1905" height="1074" alt="Screenshot 2025-08-08 110748" src="https://github.com/user-attachments/assets/326f7b52-7a70-4c24-95b1-6d6e081def4a" />



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
#### Employee
<img width="1919" height="1079" alt="Screenshot 2025-08-08 105655" src="https://github.com/user-attachments/assets/38980347-a9e6-4fc1-baa5-6eaefb83135b" />

#### Weather
<img width="1919" height="1079" alt="Screenshot 2025-08-08 111327" src="https://github.com/user-attachments/assets/f1365f48-309c-4bd0-b320-a3e6e3e33c47" />



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
#### Employee
<img width="1916" height="1078" alt="Screenshot 2025-08-08 110007" src="https://github.com/user-attachments/assets/f640acad-1547-41d2-ab96-e5de14e7620e" />

#### Weather
<img width="1919" height="1079" alt="Screenshot 2025-08-08 111609" src="https://github.com/user-attachments/assets/6bd7336e-bc1b-4c7f-bd1a-fbedf475dcb8" />



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
#### Employee
<img width="1918" height="1079" alt="Screenshot 2025-08-08 110118" src="https://github.com/user-attachments/assets/4650c98f-e77a-4966-96dc-3faa798f44f8" />

#### Weather
<img width="1919" height="1072" alt="Screenshot 2025-08-08 111851" src="https://github.com/user-attachments/assets/7e36d5bc-9e2f-4567-bde5-8f38dc2d3c68" />



### RESULT: 
  Thus the program for generating employee and weather datasets has been developed, and preprocessing has been accomplished successfully.
