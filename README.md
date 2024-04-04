# Ex03 Time Table
## Date:

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
## index.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Timetable</title>
</head>
<body style="display: flex; flex-direction: column; align-items: center; font-size: 1.5rem;">
    <img src="WEB_LOGO-01.png" width="40%">
    <h1 style="font-size:larger;">PRADEEPASRI S(212221220038)</h1>
<table border='3'  cellspacing="4" cellpadding='4'   style="width: 50%;">
<tr bgcolor="#EDCBD2">
    <th>Day/Time</th>
    <th>Monday</th>
    <th>Tuesday</th>
    <th>Wednesday</th>
    <th>Thursday</th>
    <th>Friday</th>
</tr>
<tr>
    <td bgcolor="#EDCBD2">8-10</td>
    <td style="background-color: #80C4B7;">AQLR</td>
    <td style="background-color: #80C4B7;">ETHICAL</td>
    <td style="background-color: #80C4B7;">WEB</td>
    <td style="background-color: #80C4B7;">FREE</td>
    <td style="background-color: #80C4B7;">ADC</td>
</tr>
<tr>
    <td bgcolor="#EDCBD2">10-12</td>
    <td style="background-color: #80C4B7;">FREE</td>
    <td style="background-color: #80C4B7;">IAM</td>
    <td style="background-color: #80C4B7;">ADC</td>
    <td style="background-color: #80C4B7;">FREE</td>
    <td style="background-color: #80C4B7;">FREE</td>
</tr>
<tr>
    <td bgcolor="#EDCBD2">12-1</td>
    <td colspan="5" align="center" bgcolor="#656E77">LUNCH</td>
</tr>
<tr>
    <td bgcolor="#EDCBD2">1-3</td>
    <td style="background-color: #80C4B7;">DS</td>
    <td style="background-color: #80C4B7;">IPR</td>
    <td style="background-color: #80C4B7;">DS</td>
    <td style="background-color: #80C4B7;">FREE</td>
    <td style="background-color: #80C4B7;">ADC</td>
</tr>
<tr>
    <td bgcolor="#EDCBD2">3-5</td>
    <td style="background-color: #80C4B7;">WEB</td>
    <td style="background-color: #80C4B7;">FUZZY</td>
    <td style="background-color: #80C4B7;">IPR</td>
    <td style="background-color: #80C4B7;">FREE</td>
    <td style="background-color: #80C4B7;">FUZZY</td>
</tr>
</table>
    <br>
    <table border='3' cellspacing="4" cellpadding='4' style="width: 50%;">
<tr bgcolor="#EDCBD2">
<th>S.NO</th>
<th>Subject code</th>
<th>Subject Name</th>

</tr>
<tr>
    <td>1.</td>
    <td>19AI414</td>
    <td>Fundamentals of Web Application Development</td>
</tr>
<tr>
    <td>2.</td>
    <td>19CS417</td>
    <td>Ethical Hacking Techniques</td>
</tr>
<tr>
    <td>3.</td>
    <td>19EC306</td>
    <td>Analog and Digital Communication</td>

</tr>
<tr>
    <td>4.</td>
    <td>19EC603</td>
    <td>Fuzzy Logic systems and ANN</td>
</tr>
<tr>
    <td>5.</td>
    <td>19EN618</td>
    <td>Indian Astronomy and Mathematics</td>
</tr>
<tr>
    <td>6.</td>
    <td>19EY704</td>
    <td>Advanced Quantitative and Logical Reasoning</td>
</tr>
<tr>
    <td>7.</td>
    <td>19IT405</td>
    <td>Data Structures using Python</td>
</tr>
<tr>
    <td>8.</td>
    <td>19ME531</td>
    <td>Intellectual Property Rights</td>
</tr>
</table>
</body>
</body>
</html>
```

## OUTPUT
![Screenshot 2024-04-04 182158](https://github.com/pradeepasri26/slot/assets/131433142/3e20315f-f805-4679-b436-d56887ab8252)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
