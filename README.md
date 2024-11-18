# Ex03 Time Table
## Date:18.11.2024

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
    <body>

      <center><img src="logo.png" alt="sorry" height="15%"></center>  

<table border="3" cellspacing="5" cellpadding="5" align="center">
    <caption>Slot Time Table HARISUDHAN.S (24004236)</caption>

    <tr> 
        <th>DAY/TIME</th>
        <th>MONDAY</th>
        <th>TUESDAY</th>
        <th>WEDNESDAY</th>
        <th>THURSDAY</th>
        <th>FRIDAY</th>
        <th>SATURDAY</th>
    </tr>
    <tr>
        <td>08:00 TO 10:00</td>
        <td>FREE</td>
        <td>FWAD</td>
        <td>PY&LA</td>
        <td>COM ENG</td>
        <td>FREE</td>
        <td>FREE</td>
    </tr>
    <tr>
        <td>10:00 TO 12:00</td>
        <td>COM ENG</td>
        <td>FREE</td>
        <td>FREE</td>
        <td>PY&LA</td>
        <td>FREE</td>
        <td>PY&LA</td>
    </tr>
    <tr>
        <td>12:00 TO 01:00</td>
        <td ALIGN="CENTER" COLSPAN="6">LUNCH BREAK</td>
    </tr>
    <tr>
        <td>01:00 TO 03:00</td>
        <td>CHE</td>
        <td>PY&LA</td>
        <td>MENTORMEET</td>
        <td>CHE</td>
        <td>FWAD</td>
        <td>FWAD</td>
    </tr>
</table>

<br>
<br>


<table border="1" cellpadding="10" align="center">
    <tr>
        <th>S.NO</th>
        <th>Course Code</th>
        <th>Course Name</th>
        
    </tr>
    <tr>
        <td>1.</td>
        <td>19AI301C</td>
        <td>Python and Linear Algebra(PY&LA)</td>
    </tr>
    <tr>
        <td>2.</td>
        <td>19AI414</td>
        <td>Fundamentals of Web Application Development(FWAD)</td>
    </tr>
    <tr>
        <td>3.</td>
        <td>19CY205</td>
        <td>Principles of chemistry in engineering</td>
    </tr>
    <tr><td>5.</td>
    <td>19EN101</td>
    <td>Communicative English(CE)</td></tr>
    <tr>
        <td>6.</td>
        <td>ECAM-SCOFT</td>
        <td>Mentor Meet(MM)</td>
    </tr>
</table>

</body>
</html>
```


## OUTPUT
![alt text](<Screenshot (37).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
