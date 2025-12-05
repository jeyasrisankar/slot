
## Date: 27/11/2025
## ref no: 25009010

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
<<html>
    <head>
        <title>Slot Timetable</title>
    </head>
    <body>
        <center>
            <img src="/static/logo.png" height="100" width="540">
        </center>
        <br>
        <table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="pink">
            <caption><b>SLOT TIME TABLE - JEYASRI S (25009010)</b></caption>
            <tr align="center">
                <th bgcolor="lightblue">Day/Time</th>
                <th bgcolor="lightblue">Monday</th>
                <th bgcolor="lightblue">Tuesday</th>
                <th bgcolor="lightblue">Wednesday</th>
                <th bgcolor="lightblue">Thursday</th>
                <th bgcolor="lightblue">Friday</th>
                <th bgcolor="lightblue">Saturday</th>
            </tr>
            <tr align="center">
                <th bgcolor="limegreen">8-10</th>
                <td >FREE SLOT</td>
                <td>FREE SLOT</td>
                <td>COMMUNICATIVE ENGLISH</td>
                <td>FREE SLOT</td>
                <td>FUNDAMENTALS OF C PROGRAMMING</td>
                <td>FREE SLOT</td>
            </tr>
            <tr align="center">
            <th bgcolor="limegreen">10-12</th>
            <td>COMMUNICATIVE ENGLISH</td>
            <td>FREE SLOT</td>
            <td>FUNDAMENTALS OF WEB APPLICATIONS</td>
            <td>FUNDAMENTALS OF WEB APPLICATIONS</td>
            <td>FUNDAMENTALS OF WEB APPLICATIONS</td>
            <td>FUNDAMENTALS OF WEB APPLICATIONS</td>
            </tr>
            <tr>
                <th bgcolor="limegreen">12-1</th>
                <td colspan="5" align="center">L U N C H</td>
            </tr>
            <tr align="center">
            <th bgcolor="limegreen">1-3</th>
            <td>FREE SLOT</td>
            <td>COMMUNICATIVE ENGLISH</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>COMMUNICATIVE ENGLISH</td>
            </tr>
            <tr align="center">
            <th bgcolor="limegreen">3-5</th>
            <td>FUNDAMENTALS OF C PROGRAMMING</td>
            <td>FUNDAMENTALS OF C PROGRAMMING</td>
            <td>FUNDAMENTALS OF C PROGRAMMING</td>
            <td>FUNDAMENTALS OF C PROGRAMMING</td>
            <td>FUNDAMENTALS OF WEB APPLICATIONS</td>
            <td>FREE SLOT</td>
            </tr>
         </table>
         <br>
         <table align="center"  cellspacing="2" cellpadding="4" border="2">
          <tr align="center">
            <th>S. No.</th>
            <th>Subject Code</th>
            <th>Subject Code</th>
          </tr>
          <tr> 
          <td align="center">1.</td> 
          <td align="center">19AI414</td>
          <td> Fundamentals of Web Application Development (FWAD)</td>
          </tr>
          <tr> 
          <td align="center">2.</td> 
          <td align="center">19AI302</td>
          <td> Fundamentals of C Programming (C Program)</td>
          </tr>
          <tr> 
          <td align="center">3.</td> 
          <td align="center">19EN101</td>
          <td> Communicative English (CE)</td>
          </tr>
        </table>
    </body>
    </html>
~~~

## OUTPUTS:

<img width="931" height="389" alt="Screenshot 2025-11-27 233813" src="https://github.com/user-attachments/assets/c44e3856-8abe-406d-b6a1-5db0d85000d1" />

<img width="1912" height="898" alt="Screenshot 2025-12-05 111531" src="https://github.com/user-attachments/assets/a108f057-0915-4bb4-8822-5c1b6083a34b" />


## RESULTc:
The program for creating slot timetable using basic HTML tags is executed successfully.
