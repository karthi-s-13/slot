# Ex03 Time Table
## Date: 26.04.2025

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
        <title> TIME TABLE</title>
        <style>
            img.center{
                display: block;
                margin-left: auto;
                margin-right: auto;
                width: 50%;
            }
            marquee{
                font-size: larger;
                color:red;
            }
            table,tr,th,td{
                border: 1px solid black;
                text-align: center;
            }
            table.center{
                margin-left: auto;
                margin-right: auto;
            }
            h1,h2{
                text-align: center;
            }
            body{
                text-align: center;
            }
            
            
        </style>
    </head>
    <body>
        <p text-align="center">
            <img src="logo.png" class="center">
            <h1><b>SLOT TIME TABLE - KARTHIKEYAN S (212224230116)</b></h1>
            <table width="50px" class="center">
                <tr>
                    <th bgcolor="yellow">DAY/TIME</th>
                    <th bgcolor="yellow">8AM-10AM</th>
                    <th bgcolor="yellow">10AM-12PM</th>
                    <th bgcolor="yellow">1PM-3PM</th>
                </tr>
                <tr>
                    <th bgcolor="lightgreen">MONDAY</th>
                    <td >Python programming</td>
                    <td >Assessment Hour</td>
                    <td >Machine Learning</td>
                </tr>
                <tr>
                    <th bgcolor="lightgreen">TUESDAY</th>
                    <td >Module Completion</td>
                    <td >Data Science</td>
                    <td >Adv. C Programming</td>
                </tr>
                <tr>
                    <th bgcolor="lightgreen">WEDNESDAY</th>
                    <td >Task Completion</td>
                    <td >Data Science</td>
                    <td bgcolor="">Mentors Meet</td>
                </tr>
                <tr>
                    <th bgcolor="lightgreen">THURSDAY</th>
                    <td >Assessment Hour</td>
                    <td >Adv. C Programming</td>
                    <td >Machine Learning</td>
                </tr>
                <tr>
                    <th bgcolor="lightgreen">FRIDAY</th>
                    <td >Data Science</td>
                    <td >Python Programming</td>
                    <td >Module Completion</td>
                </tr>
                <tr>
                    <th bgcolor="lightgreen">SATURDAY</th>
                    <td colspan="3">module Assessment Completion</td>
                </tr>
                
            </table>
            <table class="center">
                <h2 Subjects>
                    <tr>
                        <th bgcolor="yellow">S.NO</th>
                        <th bgcolor="yellow">SUBJECT CODE</th>
                        <th bgcolor="yellow">SUBJECT NAME</th>
                    </tr>
                    <tr>
                        <td bgcolor="lightgreen">1.</td>
                        <td>19AI301</td>
                        <td>Python Programming</td>
                        
                    </tr>
                    <tr>
                        <td bgcolor="lightgreen">2.</td>
                        <td>19AI410</td>
                        <td>Machine Learning</td>
                    </tr>
                    <tr>
                        <td bgcolor="lightgreen">3.</td>
                        <td>19AI403</td>
                        <td>Data Science</td>
                    </tr>
                    <tr>
                        <td bgcolor="lightgreen">4.</td>
                        <td>19AI305</td>
                        <td>Adv. C Programming</td>
                        
                    </tr>
                </h2>
            </table>
        </p>
    </body>
</html>
```


## OUTPUT
![alt text](<Screenshot 2025-04-26 220638.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
