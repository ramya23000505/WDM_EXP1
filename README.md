### EX1 Creation of Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform Preprocessing
### DATE: 20-04-2026
### Name: RAMYA R
### Reg No: 212223230169
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

## EMPLOYEE DATA
<img width="1919" height="877" alt="image" src="https://github.com/user-attachments/assets/5baeef97-1122-49a5-b163-2a0c825f9e2f" />

## WEATHER DATA
<img width="1919" height="1021" alt="Screenshot 2026-04-17 112334" src="https://github.com/user-attachments/assets/1d430649-aa8a-4cee-a6c9-0b79b4ccf3a6" />

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

## EMPLOYEE DATA
<img width="1916" height="871" alt="Screenshot 2026-04-17 110820" src="https://github.com/user-attachments/assets/c228bd15-5944-4a47-9a1f-7389f3c422a7" />

## WEATHER DATA
<img width="1919" height="1022" alt="Screenshot 2026-04-17 111706" src="https://github.com/user-attachments/assets/a89deb11-3927-44ab-aaa5-a19255f53ada" />

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

## EMPLOYEE DATA
<img width="1916" height="903" alt="Screenshot 2026-04-17 110924" src="https://github.com/user-attachments/assets/5fb74d86-6a8b-4a14-abe6-7086a884a505" />

## WEATHER DATA
<img width="1919" height="1020" alt="Screenshot 2026-04-17 111740" src="https://github.com/user-attachments/assets/381b83b4-654f-4112-8c1b-56782e16191a" />

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

## EMPLOYEE DATA
<img width="1919" height="871" alt="Screenshot 2026-04-17 110943" src="https://github.com/user-attachments/assets/c60259ae-04e9-4562-9f18-1a660d75aebb" />

## WEATHER DATA
<img width="1919" height="1023" alt="Screenshot 2026-04-17 111811" src="https://github.com/user-attachments/assets/9b1e3e7f-899a-4985-84da-1da0d39bf1f3" />


### RESULT: 
  Thus the program for generating employee and weather datasets has been developed, and preprocessing has been accomplished successfully.
