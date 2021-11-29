# Experiment_Time_Table

## AIM
To Write a html webpage page to display my timetable.

# ALGORITHM
### STEP 1
create a simple table using table tag
### STEP 2
Add header row using th tag
### STEP 3
Add your timetable
### STEP 4
Execute the program

# CODE
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>MY TIMETABLE</title>
<style>
table,th,td {
     border:2px solid blue;
}
table.center {
	margin-left: auto;
    margin-right: auto;
}
img {
  display: block;
  margin-left:auto;
  margin-right:auto;
}
.center
{
	text-align: center;
    list-style-position: inside;
}
ol.center li
{
	text-align: left;
    margin-left:34%;
}

</style>
</head>
<body>
<img src="https://www.saveetha.ac.in/images/WEB_LOGO-01.png" alt="institute logo" width="600" height="100">
<table class="center" style="background-color:peachpuff">
	<tr>
		<th colspan=8 style="text-align:center">TIME TABLE</th>
    </tr>
    <tr>
        <th colspan=2 style="text-align:right">Reference Number:</th>  
        <th colspan=2 style="text-align:left">21500134</th>
        <th colspan=2 style="text-align:right">Name:</th>
        <th colspan=2 style="text-align:left">Sowmiya N</th>
	</tr>
    <tr>
    	<td style="text-align:center">DAYS</td>
        <td style="text-align:center">1</td>
        <td style="text-align:center">2</td>
        <td style="text-align:center">3</td>
        <td style="text-align:center">4</td>
        <td style="text-align:center">5</td>
        <td style="text-align:center">6</td>
        <td style="text-align:center">7</td>
    <tr>
        <td style="text-align:center">Monday</td>
        <td colspan=2 style="text-align:center">Web Technology Theory Lab</td>
        <td colspan=2 style="text-align:center">Python and Linear Algebra</td>
        <td style="text-align:center">Lunch Break</td>
        <td colspan=2 style="text-align:center">Python and Linear Algebra</td>
   </tr>
   <tr>
        <td style="text-align:center">Tuesday</td>
        <td colspan=2 style="text-align:center">FREE HOUR</td>
        <td colspan=2 style="text-align:center">Mechanics Design and Modeling</td>
        <td style="text-align:center">Mentoring</td>
        <td colspan=2 style="text-align:center">Mechanics Design and Modeling</td>
   </tr>
   <tr>
        <td style="text-align:center">Wednesday</td>
        <td colspan=2 style="text-align:center">Soft Skills</td>
        <td colspan=2 style="text-align:center">Python and Linear Algebra</td>
        <td rowspan=3 style="text-align:center">Lunch Break</td>
        <td colspan=2 style="text-align:center">Web Technology Theory Lab</td>
   </tr>
       <tr>
        <td style="text-align:center">Thursday </td>
        <td colspan=2 style="text-align:center">Mechanics Design and Modeling</td>
        <td colspan=2 style="text-align:center">Python and Linear Algebra</td>       
        <td colspan=2 style="text-align:center">Mechanics Design and Modeling</td>
   </tr>
       <tr>
        <td style="text-align:center">Friday</td>
        <td colspan=2 style="text-align:center">Environmental Science</td>
        <td colspan=2 style="text-align:center">Python and Linear Algebra</td>
        <td colspan=2 style="text-align:center">Web Technology Theory Lab</td>
   </tr>
</table>
  <ol  class="center">
    <li style="font-size:20px">19AI401-Fundamentals of Web Technology</li>
    <li style="font-size:20px">19AI301-Python Programming</li>
    <li style="font-size:20px">19AI302-Engineering Design And Modeling</li>
    <li style="font-size:20px">19AI303-Engineering  Mechanics And Product Development</li>
    <li style="font-size:20px">19MA220-19MA221-Mathematics for Artificial Intelligence</li>
    <li style="font-size:20px">19EY701-Soft Skills</li>
    <li style="font-size:20px">19MC802-Environmental Science</li>
    <li style="font-size:20px">ECA051-Mentoring-AD1</li>
  </ol>
</body>
</html>
```
# OUPUT
