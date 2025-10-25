# Ex03 Time Table
## Date:25/10/2025

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
```
<html>
<head>
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src="C:\Users\admin\OneDrive\Desktop\slot timetable\slot_timetable\logo.png" height="100" width="500">
</center>
<br>
<table align="center" width="500" cellspacing="3" cellpadding="2" border="2" bgcolor="yellow">
<caption><b>SLOT TIME TABLE - KISHOR K R (212224110032)</b></caption>
<tr align="center">
<th bgcolor="cyan">Day/Time</th>
<th bgcolor="cyan">Monday</th>
<th bgcolor="cyan">Tuesday</th>
<th bgcolor="cyan">Wednesday</th>
<th bgcolor="cyan">Thursday</th>
<th bgcolor="cyan">Friday</th>
</tr>
<tr align="center">
<th bgcolor="pink">8-10</th>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
</tr>
<tr align="center">
<th bgcolor="pink">10-12</th>
<td>ENGLISH</td>
<td>C PROGRAM</td>
<td>SOFTWARE</td>
<td>FWAD</td>
<td>C PROGRAM</td>
</tr>
<tr>
<th bgcolor="pink">12-1</th>
<td colspan="6" align="center">L U N C H    B R E A K </td>
</tr>
<tr align="center">
<th bgcolor="pink">1-3</th>
<td>MATHS</td>
<td>SOFTWARE</td>
<td>MENTOR MEET</td>
<td>DATA SCIENCE</td>
<td>REASONING ABILITY</td>
</tr>
<tr align="center">
<th bgcolor="pink">3-5</th>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="2" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI414</td>
<td align ="center">FUNDAMENTALS OF WEB APPLICATION</font></b></td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI305</td>
<td align="center">ADVANCE C PROGRAMMING</td>
<td></td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19AI403</td>
<td align="center">INTRODUCTION TO DATA SCIENCE</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19CS408</td>
<td align="center">SOFTWARE ENGINEERING</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19EN101</td>
<td align="center">COMMUNICATIVE ENGLISH</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19EY709</td>
<td align="center">REASONING ABILITY</td>
</tr>
<tr>
<td align="center">7.</td>
<td align="center">19MA211</td>
<td align="center">STATISTICS AND NUMERICAL METHODS</td>
</tr>
</table>
</body>
</html>
```

## OUTPUT
![alt text](<Screenshot 2025-10-25 133522.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
