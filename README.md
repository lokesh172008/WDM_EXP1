### EX1 Creation of Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform Preprocessing
### DATE: 18-11-2026
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

Employee Data :

<img width="630" height="275" alt="539666011-3131dfa2-c4b0-4291-9703-f6d34681eeb9" src="https://github.com/user-attachments/assets/6b542b9e-7ca1-4d1f-aef8-6cea2c612dfe" />

Weather Table :

<img width="595" height="366" alt="539666146-de1e7dfc-ab09-42a8-aca6-0ccd16f356e8" src="https://github.com/user-attachments/assets/88e4c715-f280-4589-b216-dffbdfa52909" />


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

Employee Data :

<img width="613" height="248" alt="539666539-0630da89-bb70-4ced-ada5-a50a12c2dfab" src="https://github.com/user-attachments/assets/f95818c2-6075-4ae3-8b5f-
00faa2be660b" />

Weather Data :

<img width="589" height="361" alt="539666664-7bb1c8d6-83ee-48fc-8a4d-2dd66ae69519" src="https://github.com/user-attachments/assets/8429371b-bc7a-4889-a8d8-dd2f5cc3ed81" />


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

Employee Data :

<img width="666" height="262" alt="539667113-b2aabf4b-53c2-4994-b6d9-8b0eebc2d344" src="https://github.com/user-attachments/assets/6fda8800-0efb-4dfa-b073-338c5a0b6718" />

Weather Data :

<img width="722" height="372" alt="539670071-860da782-1f99-46a4-94d7-4013fdb35b33" src="https://github.com/user-attachments/assets/2df8e3ae-4331-41a3-b5cf-f3978f6358d8" />

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
Employee Data :

<img width="601" height="249" alt="539669204-8a7b94d2-740d-42d2-a94e-85a9f06e826c" src="https://github.com/user-attachments/assets/f2003f28-cb46-43bf-9454-5c339fdbce69" />

Weather Data :

<img width="574" height="359" alt="539668849-3640a1ef-6442-439b-9e7c-8c24d5e3fdeb" src="https://github.com/user-attachments/assets/8872085f-1e16-4f7a-aa24-0442197b8fde" />



### RESULT: 
  Thus the program for generating employee and weather datasets has been developed, and preprocessing has been accomplished successfully.
