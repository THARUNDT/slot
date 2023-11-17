# Ex03 Time Table
## Date:31.10.2023

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
~~~
<html>
<head>
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src="/static/logo.png" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
<caption><b>SLOT TIME TABLE - THARUN D (23013993)</b></caption>
<tr align="center">
<th bgcolor="yellow">Day/Time</th>
<th bgcolor="yellow">Monday
<th bgcolor="yellow">Tuesday
<th bgcolor="yellow">Wednesday
<th bgcolor="yellow">Thursday
<th bgcolor="yellow">Friday
</tr>
</tr> align="center">
<th bgcolor="yellow">8-10</th>
<td >FREE SLOT</td>
<td >FREE SLOT</td>
<td >FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
<td >FUNDMENTALS OF C PROGRAMMING</td>
<td >PYTHON AND LINEAR ALGEBRA</td>
</tr>
<tr align="center">
<th bgcolor="yellow">10-12</th>
<td >PRINCIPLE OF CHEMISTRY IN ENGINEERING</td>
<td >PYTHON AND LINEAR ALGEBRA</td>
<td >FREE SLOT</td>
<td >FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
<td >FREE SLOT</td>
</tr>
<tr>
<th bgcolor="yellow">12-01</th>
<td colspan="5" align="center"> L U N C H</td>
</tr>
<tr>
<tr align="center">
<th bgcolor="yellow">01-03</th>
<td >SOFT SKILLS</td>
<td >FREE SLOT</td>
<td >FUNDAMENTALS OF C PROGRAMMING</td>
<td >PHYSICS FOR QUANTUM COMPUTING</td>
<td >FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
</tr>
<tr align="center">
<th bgcolor="yellow">03-05</th>
<td >FREE SLOT</td>
<td >PHYSICS FOR QUANTUM COMPUTING</td>
<td >PYTHON AND LINEAR ALGEBRA</td>
<td >PYTHON AND LINEAR ALGEBRA</td>
<td >PRINCIPLE OF CHEMISTRY IN ENGINEERING</td>
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>No.</th>
<th>Subject code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI414</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT(FWAD)</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI304</td>
<td>FUNDAMENTALS OF C PROGRAMMING(C PROGRAM)</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19AI301C</td>
<td>PYTHON AND LINEAR ALGEBRA(PYTHON PROGRAM AND LINEAR ALGEBRA)</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19CY205</td>
<td>PIRNCIPLE OF CHEMISTRY IN ENGINEERING</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19PH214</td>
<td>PHYSICS FOR QUANTUM COMPUTING</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19EY701</td>
<td>SOFT SKILLS(SS)</td>
</tr
</table>
</body>
</html>
~~~

## OUTPUT
![Screenshot 2023-11-17 141549](https://github.com/THARUNDT/slot/assets/144871537/635dd099-7590-42c5-b29d-fa147edc8ecd)




## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
