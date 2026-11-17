# Ex04 Time Table
## Date:17-11-2026

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create an App inside the Django project.

### STEP 2
Create a static folder uder the created App and insert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html with the relevant attributes.

### STEP 4
Add rows using ```<tr>``` tag.

### STEP 5
Add your course schedule using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
<html>
    <head>
        <title>My Time Table</title>
    </head>
    <body>
        <img src="logo.png" width="1500" height="200" align="center">
        <table border="1" cellspacing="2" cellpadding="10" bgcolor="pink" align="center">
        <h3 align="center">SLOT TIME TABLE - DEEPALAKSHMI S (26014071)</h3>
        <tr bgcolor="aqua" align="center">
            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
            <th>Saturday</th>
        </tr>
        <tr align="center">
        <td bgcolor="aqua"><b>8.00 - 9.30</b></td>
        <td>DE</td>
        <td>FREE SLOT</td>
        <td>FWAD</td>
        <td>ENG</td>
        <td>MAT</td>
        <td>CYBER</td>
        </tr>
        <tr align="center">
            <td bgcolor="aqua"><b>9.45 - 11.15</b></td>
            <td>FWAD</td>
            <td colspan="2" align="center">FREE SLOT</td>
            <td>MAT</td>
            <td>FREE SLOT</td>
            <td>DE</td>
        </tr>
        <tr align="center">
        <td bgcolor="aqua"><b>11.15 - 1.15</b></td>
        <td colspan="6" align="center">LUNCH</td>
        </tr>
        <tr align="center">
            <td bgcolor="aqua"><b>1.15 - 2.45</b></td>
            <td>FREE SLOT</td>
            <td>FWAD</td>
            <td>FREE SLOT</td>
            <td>CYBER</td>
            <td>FREE SLOT</td>
            <td>ENG</td>
        </tr>
        <tr align="center">
            <td bgcolor="aqua"><b>3.00 - 4.30</b></td>
            <td colspan="2" align="center">FREE SLOT</td>
            <td>PYTHON</td>
            <td>BEEE</td>
            <td>PYTHON</td>
            <td>PYTHON</td>
        </tr>

        <br><br>
        
        <table border="1" cellspacing="2" cellpadding="10" align="center">
            <tr align="center">
                <th>S.NO.</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr align="center">
                <td>1.</td>
                <td>19AI414</td>
                <td>Fundamentals of Web Application Development(FWAD)</td>
            </tr>
            <tr align="center">
                <td>2.</td>
                <td>19EE404</td>
                <td>Digital Electronics(DE)</td>
            </tr>
            <tr align="center">
                <td>3.</td>
                <td>19AI301</td>
                <td>Python Programming(PYTHON)</td>
            </tr>
            <tr align="center">
                <td>4.</td>
                <td>19EN101</td>
                <td>Communicative English(ENG)</td>
            </tr>
            <tr align="center">
                <td>5.</td>
                <td>19MA211</td>
                <td>Statistics and Numerical Methods(MAT)</td>
            </tr>
            <tr align="center">
                <td>6.</td>
                <td>19CS418</td>
                <td>Cyber Law and Compliance(CYBER)</td>
            </tr>
            <tr align="center">
                <td>7.</td>
                <td>19EE305</td>
                <td>Basic Electrical,Electronics and Measurement Engineering(BEEE)</td>
            </tr>

    </body>

</html>
```

## OUTPUT
![alt text](<Screenshot (18).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
