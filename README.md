# Ex04 Places Around Me
## Date: 

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

map.html

<html>
<head>
<title>MY CITY</title>
</head>
<body>
<h1 align="center">
<font color="black"><b>Vellore</b></font>
</h1>
<h3 align="center">
<font color="green"><b>Surjith.D(24900287)</b></font>
</h3>
<center>
<img src="map.png" usemap="#image-map">

<map name="image-map">
    <area target="_self" alt="Spartanz Fitness" title="Spartanz Fitness" href="fitness.html" coords="657,687,483,572" shape="rect">
    <area target="_self" alt="Government Hospital" title="Government Hospital" href="hospital.html" coords="464,142,642,231" shape="rect">
    <area target="_self" alt="RTO Office Melur" title="RTO Office Melur" href="office.html" coords="1154,644,69" shape="circle">
    <area target="_self" alt="Ganesh Theatre Complex" title="Ganesh Theatre Complex" href="theatre.html" coords="723,299,840,380" shape="rect">
    <area target="_self" alt="Poorvika Mobiles Melur" title="Poorvika Mobiles Melur" href="mobiles.html" coords="509,322,661,430" shape="rect">
</map>
</center>
</body>
</html>

office.html

<html>
<head>
<title>MY NATIVE</title>
</head>
<body bgcolor="orange">
<h1 align="center">
<font color="white"><b>Vellore</b></font>
</h1>
<h3 align="center">
<font color="pink"><b>RTO office Gudiyattam</b></font>
</h3>
<hr size="4" color="white">
<p align="justify">
<font face="Georgia" size="6">
    The RTO Office in Gudiyattam, Vellore offers a wide range of services related to vehicle registration, licensing and  t
    the Vellore RTO is also responsible for collection of taxes, issuing permits. 
</font>
</p>
</body>
</html>


## OUTPUT
![image](https://github.com/user-attachments/assets/b4a05e7d-3689-44bb-b102-e5a62368d0b0)
![image](https://github.com/user-attachments/assets/adbc4128-9d13-48a0-98b0-567e46969161)

## RESULT
The program for implementing image maps using HTML is executed successfully.
