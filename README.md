# Ex03 Time Table
## Date:14.03.2024

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
        <title>MY TIME TABLE</title>
    </head>
    <body>
        <center>
        <img src="logo.png" height="100" width="777">
        </center>
        <table align="center" border="2" cellspacing="12" cellpadding="12" height="25" width="50">
            <h1 align="center" >Slot Time Table-K.Abhineswar Reddy(212223040084)</h1>
            <tr>
            
                <th bgcolor="red">DAY/TIME</th>
                <th bgcolor="red">MONDAY</th> 
                <th bgcolor="red">TUESDAY</th>
                <th bgcolor="red">WEDNESDAY</th>
                <th bgcolor="red">THURSDAY</th>
                <th bgcolor="red">FRIDAY</th>
                <th bgcolor="red">SATURDAY</th>
            </tr>
            <tr>
                <td bgcolor="red">8-10</td>
                <td bgcolor="green">free slot</td>
                <td bgcolor="green">free slot</td>
                <td bgcolor="green">che</td>
                <td bgcolor="green">free slot</td>
                <td bgcolor="green">web</td>
                <td bgcolor="green">maths</td>
            </tr>
            <tr>
                <td bgcolor="red">10-12</td>
                <td bgcolor="green">free slot</td>
                <td bgcolor="green">free slot</td>
                <td bgcolor="green">free slot</td>
                <td bgcolor="green">maths</td>
                <td bgcolor="green">c program</td>
                <td bgcolor="green">che</td>
            </tr>
            <td bgcolor="red">12-01</td>
                <td align="center" colspan="6" bgcolor="yellow">LUNCH</td>
            </tr>
            <tr>
                <td bgcolor="red">01-03</td>
                <td bgcolor="green">creative</td>
                <td bgcolor="green">web</td>
                <td bgcolor="green">english</td>
                <td bgcolor="green">web</td>
                <td bgcolor="green">computer networks</td>
                <td bgcolor="green">free slot</td>
            </tr>
            <tr>
                <td bgcolor="red">03-05</td>
                <td bgcolor="green">c program</td>
                <td bgcolor="green">free slot</td>
                <td bgcolor="green">computer networks</td>
                <td bgcolor="green">free slot</td>
                <td bgcolor="green">english</td>
                <td bgcolor="green">free slot</td>
            </tr>
        <table align="center" border="3" cellspacing="2" cellpadding="4">
            <tr>
                <th>S.NO</th>
                <th>SUBJECT CODE</th>
                <th>SUBJECT NAME</th>
            </tr>
            <tr>
                <td>1.</td>
                <td>19AI304</td>
                <td>Fundamentals of c Programming</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>19AI414</td>
                <td>Fundamentals of web application development</td>
            </tr>
            <tr>
                <td>3.</td>
                <td>19CS406</td>
                <td>Computer Networks</td>
            </tr>
            <tr>
                <td>4.</td>
                <td>19CY205</td>
                <td>Principles of chemistry in Engineering</td>
            </tr>
            <tr>
                <td>5.</td>
                <td>19EN101</td>
                <td>Communicative English</td>
            </tr>
            <tr>
                <td>6.</td>
                <td>19EY702</td>
                <td>Creative skills for Communication</td>
            </tr>
            <tr>
                <td>7.</td>
                <td>19MA222</td>
                <td>Probability and Queueing Models</td>
            </tr>
            <br>
        </table>

        </table>
    </body>
</html>
```

## OUTPUT
![alt text](<Screenshot (2).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
