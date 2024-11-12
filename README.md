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

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Slot Timetable</title>
    <style>
        .table1{
            background-color: rgb(249, 201, 181);
            border-color: black;
            text-align: center;
            width: 800px;
            height: 250px;
        }
        .table2{
            border-color: black;
            text-align: center;
            width: 800px;
            height: 250px; 
        }
        .name{
            padding-left: 185px;
        }
        .row1{
            background-color: lightblue;
        }
        .c1{
            background-color: lightblue;
        }
    </style>
</head>
<body>
    <img src = "http://training.saveetha.in/pluginfile.php/1/core_admin/logo/0x150/1623542614/logo_1.png" width = "800" height="150">
    <h3 class = "name">SLOT TIMETABLE - ADITAAYAN (212223040006)</h3>
    <table border="1" class = "table1">
        <tr class = "row1">
            <th class="c1">Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
            <th>Saturday</th>
        </tr>
        <tr>
            <td class="c1">8-10</td>
            <th>FREE SLOT</th>
            <td>OS</td>
            <td>SE</td>
            <td>ML</td>
            <td>FWAD</td>
            <td>OS</td>
        </tr>
        <tr>
            <td class="c1">10-12</td>
            <td>ML</td>
            <th>POC</th>
            <td>FWAD</td>
            <td>PQC</td>
            <td>POC</td>
            <td>CD</td>
            
        </tr>
        <tr>
            <td class="c1">12-1</td>
            <th colspan="6">L U N C H</th>
        </tr>
        <tr>
            <td class="c1">1-3</td>
            <td>FREE SLOT</td>
            <td>CD</td>
            <th colspan="3">FREE SLOT</th>
            <td>CRYPTO</td>
            
        </tr>
        <tr>
            <td class="c1">3-5</td>
            <th>SE</th>
            <td>FWAD</td>
            <td>CRYPTO</td>
            <td>FREE SLOT</td>
            <td>PQC</td>
            <td>FREE SLOT</td>
        </tr>
    </table>
    <br>
    <br>
    <table border="1" class="table2">
        <tr>
            <th>S.No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td>1.</td>
            <td>19PH214</td>
            <td>Physics for quantum computing (POC)</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>19CS409</td>
            <td>Compiler Design (CD)</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>19CY205</td>
            <td>Principles of Chemistry (POC)</td>
        </tr>
        <tr>
            <td>4.</td>
            <td>19CS408</td>
            <td>Software Engineering (SE)</td>
        </tr>
        <tr>
            <td>5.</td>
            <td>19CS415</td>
            <td>Cryptography</td>
        </tr>
        <tr>
            <td>6.</td>
            <td>19AI410</td>
            <td>Introduction to Machine Learning (ML)</td>
        </tr>
        <tr>
            <td>7.</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Applications Development (FWAD)</td>
        </tr>
    </table>
</body>
</html>
```

## OUTPUT

![Screenshot 2024-10-06 202603](https://github.com/user-attachments/assets/acd054ab-3bb5-425f-a1ea-3dcdfb88c479)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
