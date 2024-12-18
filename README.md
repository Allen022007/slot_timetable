# Ex03 Time Table
## Date: 16/11/2024

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
<!DOCTYPE html>
<html>
    <head>
        
    </head>
    <body>
        <center>
            <img src='logo.png' height="100" width="540"
        </center>
        <br>
    <table border="2" cellpadding="5" cellspacing="10" bgcolor="lightblue" align="center">
        <caption><b>SLOT TIME TABLE - W ALLEN (24900645)</b></caption>
        <tr>
        <th>DAYS</th>
        <th>8 to 10</th>
        <th>10 to 12</th>
        <th>1 to 3</th>
        <th>3 to 5</th>
        </tr>
        <tr>
        <td>Monday</td>
        <td></td>
        <td bgcolor="yellow">Web dev</td>
        <td bgcolor="blue">CDS</td>
        <td></td>
        </tr>
        <tr >
            <td >Tuesday</td>
            <td bgcolor="green">Prototyping of IoT systems</td>
            <td></td>
            <td bgcolor="red">Digital Electronics</td>
            <td></td>
        </tr>
        <tr>
            <td>Wednesday</td>
            <td bgcolor="red">Digital Electronics</td>
            <td bgcolor="yellow">Wed dev</td>
            <td>Mentor Meet</td>
            <td bgcolor="green">Prototyping of IoT systems</td>
        </tr>
        <tr>
            <td>Thursday</td>
            <td bgcolor="gold">PQC</td>
            <td bgcolor="orange">EMPD</td>
            <td bgcolor="pink">Comm English</td>
            <td></td>
        </tr>
        <tr>
            <td>Friday</td>
            <td></td>
            <td bgcolor="pink">Comm English</td>
            <td bgcolor="orange">EMPD</td>
            <td></td>
        </tr>
        <tr>
            <td>Saturday</td>
            <td></td>
            <td bgcolor="gold">PQC</td>
            <td bgcolor="yellow">Web dev</td>
            <td></td>
        </tr>
    </table>
    <br>
    <table border="2" cellpadding="5" cellspacing="10" bgcolor="lightblue" align="center">
        <tr>
        <th>S.no</th>
        <th>Subject code</th>
        <th>Subject Name</th>
        </tr>
        <tr>
            <td>1</td>
            <td>19AI303</td>
            <td>Engineering Mechanic and Product Development</td>
        </tr>
        <tr>
            <td>2</td>
            <td>19AI404</td>
            <td>Fundamental of Web Application Development</td>
        </tr>
        <tr>
            
            <td>3</td>
            <td>19CS420</td>
            <td>Prototyping of IoT systems</td>
           
        </tr>
        <tr>
            
            <td>4</td>
            <td>19EE404</td>
            <td>Digital Electronics</td>
            
        </tr>
        <tr>
            
            <td>5</td>
            <td>19EN101</td>
            <td>Communicative English</td>
            
        </tr>
        <tr>
            
            <td>6</td>
            <td>19EY708</td>
            <td>Career Development Skills</td>
            
        </tr>
        <tr>
            
            <td>7</td>
            <td>SH3214</td>
            <td>Physics for Quantum Computing</td>
            
        </tr>
    </table>
    </body>
</html>
~~~

## OUTPUT

![alt text](<Screenshot 2024-11-19 110644.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
