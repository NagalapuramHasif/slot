# Ex03 Time Table
## Date:22.03.2024

## AIM To write a html webpage page to display your slot timetable.

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
            <img src="/static/logo.png" height="100"width="540">
        </center>
        <br>
        <table align="center" width="540">
            <caption><b>SLOT TIMETABLE NAGALAPURAM HASIF (212223100036)</b></caption>
            <tr align="center">
                <th bgcolor="yellow">Day/Time</th>
                <th bgcolor="yellow">Monday</th>
                <th bgcolor="yellow">Tuesday</th>
                <th bgcolor="yellow">Wednesday</th>
                <th bgcolor="yellow">Thursday</th>
                <th bgcolor="yellow">Friday</th>
            </tr>
            <tr align="center">
                <th bgcolor="pink">8-10</th>
                <td bgcolor="blue">FINANCIAL ACCOUNTING</td>
                <td bgcolor="blue">DIGITAL ELECTRONICS</td>
                <td bgcolor="blue">BEEE</td>
                <td bgcolor="blue">DIGITAL ELECTRONICS</td>
                <td bgcolor="blue">FUNDAMENTALS OF WEB APPLICATION </td>
            </tr>
            <tr align="centre">
                <th bgcolor="pink">10-12</th>
                <td bgcolor="orange">SOFTWARE ENGINEERING</td>
                <td bgcolor="orange">FUNDAMENTALS OF WEB APPLICATION DEVLOPMENT</td>
                <td bgcolor="orange">SOFTWARE ENGINEERING</td>
                <td bgcolor="orange">COMPUTER ARCHITECHTURE</td>
                <td bgcolor="orange">FREE SLOT</td>
            </tr>
            <tr align="centre">
                <th bgcolor="pink">12-1</th>
                <td bgcolor="light blue">LUNCH</td>
                <td bgcolor="light blue">LUNCH</td>
                <td bgcolor="light blue">LUNCH</td>
                <td bgcolor="light blue">LUNCH</td>
                <td bgcolor="light blue">MENTOR MEET</td>
            </tr>
            <tr align="centre">
                <th bgcolor="pink">1-3</th>
                <td bgcolor="green">BEEE</td>
                <td bgcolor="green">FREE SLOT</td>
                <td bgcolor="green">FREE SLOT</td>
                <td bgcolor="green">COMPUTER ARCHITECTURE</td>
                <td bgcolor="green">FREE SLOT</td>
            </tr>
            <tr align="centre">
                <th bgcolor="pink">3-5</th>
                <td bgcolor="blue green">FREE SLOT</td>
                <td bgcolor="blue green">FREE SLOT</td>
                <td bgcolor="blue green">FUNDAMENTALS OF WEB APPLICATION DEVLOPMENT</td>
                <td bgcolor="blue green">FREE SLOT</td>
                <td bgcolor="blue green">FINANCIAL ACCOUNTING</td>
            </tr>
        </table>
        <br>
        <table align="center" cellspacing="2" cellpadding="4" border="2">
            <tr align="center">
                <th>S.No.</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr> 
            <tr>
                <td align="center">1.</td>
                <td align="center">19AI414</td>
                <td>Fundamentals of Web Application Development (FWAD)</td>
            </tr>
            <tr>
                <td align="center">2.</td>
                <td align="center">19MS154</td>
                <td>BASIC FINANCIAL ACCOUNTING</td>
            </tr>
            <tr>
                <td align="center">3.</td>
                <td align="center">19CS408</td>
                <td>SOFTWARE ENGRINEEING (SE)</td>
            </tr>
            <tr>
                <td align="center">4.</td>
                <td align="center">19EE305</td>
                <td>BEEE</td>
            </tr>
            <tr>
                <td align="center">5.</td>
                <td align="center">19EE404</td>
                <td>DIGITAL ELECTRONICS</td>
            </tr>
            <tr>
                <td align="center">6.</td>
                <td align="center">19CS305</td>
                <td>COMPUTER ARCHITECTURE</td>
            </tr>
            <tr>
                <td align="center">7.</td>
                <td align="center">ECA-M</td>
                <td>MENTOR MEET</td>
            </tr>
        </table>
    </body>
</html>


```

## OUTPUT

![alt text](<Screenshot 23.03.2024.jpg>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
