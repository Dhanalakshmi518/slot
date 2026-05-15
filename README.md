# Ex03 Time Table
## Date:22.09.2025

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
        <title>
            SLOT TIME TABLE
        </title>
    </head>
    <body>
        <center>
            <img src="/static/logo.jpeg" height="100" width="560">

        </center>
        <table align="center" width="560" cellspacing="2" border="5" bgcolor="cyan">
        <caption><b>TIMETABLE - DHANALAKHMI (212225040063)</b></caption>
        <tr align="center">
            <th bgcolor="lightyellow">Day/Time</th>
            <th bgcolor="lightyellow">MONDAY</th>
            <th bgcolor="lightyellow">TUESDAY</th>
            <th bgcolor="lightyellow">WEDNESDAY</th>
            <th bgcolor="lightyellow">THURSDAY</th>
            <th bgcolor="lightyellow">FRIDAY</th>
            <th bgcolor="lightyellow">SATURDAY</th>
        </tr>
        <tr align="center">
            <th bgcolor="lightyellow">8.00 - 10.00</th>
            <td>com.eng</td>
            <td>c-pro</td>
            <td>web</td>
            <td>com.eng</td> 
            <td>free</td>    
            <td>web</td>   
        </tr>
        <tr align="center">
            <th bgcolor="lightyellow">10.00 - 12.00</th>
            <td>free</td>
            <td>c-pro</td>
            <td>com.eng</td>
            <td>com.eng</td> 
            <td>free</td>    
            <td>web</td>   
        </tr>
        <tr>
            <th bgcolor="lightyellow">12.00 - 1.00</th>
            <td colspan="2" align="center"></td>
        </tr>
        <tr align="center">
            <th bgcolor="lightyellow">1.00 - 3.00</th>
            <td>com.eng</td>
            <td>c-pro</td>
            <td>web</td>
            <td>com.eng</td> 
            <td>free</td>    
            <td>web</td>   
        </tr>
        <tr align="center">
            <th bgcolor="lightyellow">3.00 - 5.00</th>
            <td>free</td>
            <td>c-pro</td>
            <td>free</td>
            <td>com.eng</td> 
            <td>free</td>    
            <td>web</td>   
        </tr>


        </table>
    </body>
</html>
```
## OUTPUT

![alt text](<Screenshot (59).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
