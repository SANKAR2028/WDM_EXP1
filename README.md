### EX1 Creation of Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform Preprocessing
### DATE: 23/01/26
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
@attribute name string
@attribute id numeric
@attribute mobile numeric
@attribute gender {male,female}
@attribute salary {low,medium,high}
@data
SANKAR,10,9342765071,male,,high
RAVI,11,9597449515,male,low
RABIN,12,5685856578,male,high
KRISHNA,13,2565457585,male,low
KARUVA,14,9565457885,male,low



--------------
Weather Data
---------------
@relation weather
@attribute temeperature numeric
@attribute Windy {true,false}
@attribute humidity numeric
@attribute windy {true,false}
@attribute play {yes,no}
@attribute outlook {sunny,overcast,rainy}
@data
80,true,70,false,yes,sunny
80,false,75,true,no,sunny
75,false,78,true,no,rainy
85,true,82,false,yes,overcast
70,false,90,true,yes,overcast
78,true,86,true,yes,rainy
```
3) After that the file is saved with .arff file format.
4) Minimize the arff file and then open Start -> Programs -> weka-3-4.
5) Click on weka-3-4, then Weka dialog box is displayed on the screen.
6) In that dialog box there are four modes, click on explorer.
7) Explorer shows many options. In that click on ‘open file’ and select the arff file
8) Click on edit button which shows employee table on weka.

### OUTPUT:

<img width="490" height="283" alt="image" src="https://github.com/user-attachments/assets/899d2195-d950-4410-a242-c1979acd047f" />
<img width="715" height="292" alt="image" src="https://github.com/user-attachments/assets/36210490-9ca2-4b77-a2b4-3aaf779695cd" />


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
<img width="573" height="273" alt="Screenshot 2026-01-23 155606" src="https://github.com/user-attachments/assets/8ceb64cb-f924-4e09-a176-f8c1aec19737" />

<img width="664" height="325" alt="Screenshot 2026-01-23 161655" src="https://github.com/user-attachments/assets/66b23ba2-213c-4443-8d9b-2277223b8038" />

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
<img width="477" height="275" alt="Screenshot 2026-01-23 155658" src="https://github.com/user-attachments/assets/122e48ec-e1ac-4a34-aa63-a27a794f3e67" />

<img width="463" height="272" alt="Screenshot 2026-01-23 161256" src="https://github.com/user-attachments/assets/e337226a-0651-4280-b655-92e2af263206" />
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
<img width="477" height="269" alt="Screenshot 2026-01-23 155738" src="https://github.com/user-attachments/assets/687e1f7c-f986-4934-acf9-987304f57003" />
<img width="755" height="319" alt="Screenshot 2026-01-23 161726" src="https://github.com/user-attachments/assets/38b0513f-8b55-48ef-89c1-59938d4dc988" />

### RESULT: 
  Thus the program for generating employee and weather datasets has been developed, and preprocessing has been accomplished successfully.
