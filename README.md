# Ex03 Time Table
## Date:14-03-2024

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
<title> Time Table </title>
</head>

<body bgcolor="grey">

<center>
<img src="logo.png" height="100" width="540">
</center>
<br>

<table align="center" width="800" cellspacing="3" cellpadding="14" border="2" bgcolor="charcoal">
<caption> <b> SLOT TIME TABLE - GAYATHRI (212223220024) </b> </caption>

<tr align="center">
<th bgcolor="lightblue"> Day / Time </th>
<th bgcolor="lightblue"> 8 - 10 </th>
<th bgcolor="lightblue"> 10 - 12 </th>
<th bgcolor="lightblue"> 12 - 1 </th>
<th bgcolor="lightblue"> 1 - 3 </th>
<th bgcolor="lightblue"> 3 - 5 </th>
</th>

<tr align="center">
<th bgcolor="lightblue"> Monday </th>
<td bgcolor="pink">Basic Electrical,Electronics and Measurement Engineering </td>
<td bgcolor="pink">Free Slot</td>
<td rowspan="6" bgcolor="pink"> Lunch </td>
<td bgcolor="pink"> Free Slot</td>
<td bgcolor="pink"> C programing</td>
</tr>

<tr align="center">
<th bgcolor="lightblue"> Tuesday </th>
<td colspan="2" bgcolor="pink">Free Slot</td>
<td bgcolor="pink"> Fundamentals of Web Application Development</td>
<td bgcolor="pink"> Free Slot </td>
</tr>

<tr align="center">
<th bgcolor="lightblue"> Wednesday </th>
<td colspan="2" bgcolor="pink">Free Slot</td>
<td bgcolor="pink"> Digital Electronics </td>
<td bgcolor="pink">Computer Networks </td>
</tr>

<tr align="center">
<th bgcolor="lightblue"> Thursday </th>
<td bgcolor="pink"> Operating System </td>
<td bgcolor="pink"> probability </td>
<td bgcolor="pink">Fundamentals of Web Application Development </td>
<td bgcolor="pink"> Free Slot </td>
</tr>
<tr align="center">
<th bgcolor="lightblue"> Friday </th>
<td bgcolor="pink"> Fundamentals of Web Application Development  </td>
<td bgcolor="pink"> C Programming</td>
<td bgcolor="pink"> Computer Networks </td>
<td bgcolor="pink"> Operating System </td>
</tr>
<tr align="center">
<th bgcolor="lightblue"> Saturday </th>
<td bgcolor="pink"> Probability  </td>
<td bgcolor="pink"> Digital Electronics</td>
<td bgcolor="pink"> Basic Electrical,Electronics and Measurement Engineering</td>
<td bgcolor="pink">Free Slot</td>
</tr>
</table>
<br>
<br>
<table align="center" cellspacing="3" cellpadding="15" border="2" bgcolor="charcoal">

<tr align="center">
<th bgcolor="lightblue"> S.No. </th>
<th bgcolor="lightblue"> Subject Code </th>
<th bgcolor="lightblue"> Subject Name </th>
</tr>

<tr>
<th align="center" bgcolor="lightblue"> 1. </th>
<td align="center" bgcolor="pink"> 19AI414 </td>
<td bgcolor="pink"> Fundamentals of Web Application Development </td>
</tr>

<tr>
<th align="center" bgcolor="lightblue"> 2. </th>
<td align="center" bgcolor="pink"> 19AI304 </td>
<td bgcolor="pink">C Programming  </td>
</tr>

<tr>
<th align="center" bgcolor="lightblue"> 3. </th>
<td align="center" bgcolor="pink"> 19CS405</td>
<td bgcolor="pink"> Operating System </td>
</tr>

<tr>
<th align="center" bgcolor="lightblue"> 4. </th>
<td align="center" bgcolor="pink"> 19MA222 </td>
<td bgcolor="pink"> Probability </td>
</tr>

<tr>
<th align="center" bgcolor="lightblue"> 5. </th>
<td align="center" bgcolor="pink"> 19EE305 </td>
<td bgcolor="pink"> Basic Electricals, Electronics and Measurement Engineering </td>
</tr>

<tr>
<th align="center" bgcolor="lightblue"> 6. </th>
<td align="center" bgcolor="pink"> 19CS406 </td>
<td bgcolor="pink"> Computer Networks </td>
</tr>

<tr>
<th align="center" bgcolor="lightblue"> 6. </th>
<td align="center" bgcolor="pink"> 19EE404 </td>
<td bgcolor="pink"> Digital Electronics </td>
</tr>
</table>


</body>
</html>
```

## OUTPUT
![alt text](t1.png)
![alt text](t2.png)




## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
