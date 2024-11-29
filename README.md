# Ex04 Places Around Me
## Date: 27/11/24

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
```
cafe.html
<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="pink"
<h1 align="center">
<font color="red"><b>Sankarapuram</b></font>
</h1>
<h3 align="center">
<font color="yellow"><b>Prince Cafe</b></font>
</h3>
<hr size="3" color="blue">
<p align="justify">
<font face="Georgia" size="5">
	 The Veterans Affairs Office (VAO) located in avatti dedicated to supporting and advocating for military veterans. It provides a range of services, including healthcare, disability compensation, education benefits, and housing assistance. The VAO plays a vital role in ensuring that veterans receive the care and support they deserve after their service to the nation. 
</font>
</p>
</body>
</html>

theatre.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="voilet"
<h1 align="center">
<font color="pink"><b>Sankarapuram</b></font>
</h1>
<h3 align="center">
<font color="yellow"><b>theatre</b></font>
</h3>
<hr size="3" color="blue">
<p align="justify">
<font face="Georgia" size="5">
	NVN Theatre - East Street is a popular theatre located at State Highway 6, Near Malar Makkal Marunthagam, East Street, East, Sankarapuram. NVN Theatre - East Street has 1 screens. Movies now showing at NVN Theatre - East Street are NONE.
</font>
</p>
</body>
</html>

bus stand.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="grey"
<h1 align="center">
<font color="blue"><b>Sankarapuram</b></font>
</h1>
<h3 align="center">
<font color="white"><b>Sankarapuram bus stand</b></font>
</h3>
<hr size="3" color="blue">
<p align="justify">
<font face="Georgia" size="5">
    A bus stand, also called a bus bay, or bus stance, is a designated parking location where a bus or coach waits out of service between scheduled public transport services. 'Bus stand' is also often an alternative name for specific bus stops inside a bus station.
</font>
</p>
</body>
</html>

maligai.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="yellow"
<h1 align="center">
<font color="green"><b>Sankarapuram</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>sakthi maligai</b></font>
</h3>
<hr size="3" color="blue">
<p align="justify">
<font face="Georgia" size="5">
    SAKTHI MALIGAI is located at 1\131, Kamalam Illam, T Pudupalayam, 1, Main Road Vikiravandi Tk Viluppuram, Tamil Nadu, 605652 India
</font>
</p>
</body>
</html>

school.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="blue"
<h1 align="center">
<font color="red"><b>Sankarapuram</b></font>
</h1>
<h3 align="center">
<font color="yellow"><b>Danish mission primary school</b></font>
</h3>
<hr size="3" color="blue">
<p align="justify">
<font face="Georgia" size="5">
	 DANISH MISSION PRIMARY SCHOOL, KALLAKURICHI was established in 1915 and it is managed by the Pvt. Aided. It is located in Urban area. It is located in KALLAKURICHI block of VILUPPURAM district of Tamil Nadu. The school consists of Grades from 1 to 5.
</font>
</p>
</body>
</html>

map.html

<html>
<head>
<title>MyCity</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Sankarapuram</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Suruthi(24013561)</b></font>
</h3>
<center>
<img src="map.png" usemap="#MyCity" height="610" width="1450">
<map name="MyCity">
     <area shape="rect" coords="200,300,500,500" title="Prince Cafe" href="Cafe.html">
     <area shape="circle" coords="250,300,60" title="sankarapuram bus stand" href="bus stand.html">
     <area shape="circle" coords="700,210,60" title="Danish mission primary school" href="school.html">
     <area shape="circle" coords="850,220,100" title="NVM Theatre" href="theatre.html">
     <area shape="circle" coords="750,210,60" title="sakthi maligai" href="maligai.html">
</map>
</center>
</body>
</html>


```


## OUTPUT

![alt text](<Screenshot (15).png>)
![alt text](<Screenshot (16).png>)
![alt text](<Screenshot (18).png>)
![alt text](<Screenshot (19).png>)
![alt text](<Screenshot (20).png>)
![alt text](<Screenshot (21).png>)


## RESULT
The program for implementing image maps using HTML is executed successfully.
