# Ex03 Time Table
# Date:
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using <table> tag in html.

## STEP 4
Add header row using <th> tag.

## STEP 5
Add your timetable using <td> tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TimeTable</title>
</head>
<body>
    <img src="./Screenshot 2024-10-10 140017.png" alt="Saveetha Engineering College Image">
    <p><b>Ahamed Sahul's Timetable</b></p>
    <table border="12" style="margin-bottom: 30px;">
        <tr>
            <th style="background-color: yellow;">DAYS</th>
            <th style="background-color: yellow;">8-10</th>
            <th style="background-color: yellow;">10-12</th>
            <th rowspan="7"><p style="writing-mode: vertical-rl;">LUNCH</p></th>
            <th style="background-color: yellow;">1-3</th>
            <th style="background-color: yellow;">3-5</th>
        </tr>
        <tr>
            <td style="background-color: yellow;">MONDAY</td>
            <td>FREE SLOT</td>
            <td>WEB APPLICATION</td>
            <td>CHEMISTRY</td>
            <td>FREE SLOT</td>
        </tr>
        <tr>
            <td style="background-color: yellow;">TUESDAY</td>
            <td>FREE SLOT</td>
            <td>CALCULUS</td>
            <td>EDM</td>
            <td>FREE SLOT</td>
        </tr>
        <tr>
            <td style="background-color: yellow;">WEDNESDAY</td>
            <td>EDM</td>
            <td>PYTHON</td>
            <td>MENTOR MEETING</td>
            <td>FREE SLOT</td>
        </tr>
        <tr>
            <td style="background-color: yellow;">THURSDAY</td>
            <td>FREE SLOT</td>
            <td>CHEMISTRY</td>
            <td>WEB APPLICATION</td>
            <td>FREE SLOT</td>
        </tr>
        <tr>
            <td style="background-color: yellow;">FRIDAY</td>
            <td>FREE SLOT</td>
            <td>DIGITAL ELECTRONICS</td>
            <td>PYTHON</td>
            <td>FREE SLOT</td>
        </tr>
        <tr>
            <td style="background-color: yellow;">SATURDAY</td>
            <td>DIGITAL ELECTRONICS</td>
            <td>CAREER DEVELOPMENT SKILL</td>
            <td>CALCULUS</td>
            <td>WEB APPLICATION</td>
        </tr>
    </table>

    <table border="5">
       <tr>
          <th>S.no</th>
          <th>SUBJECT CODE</th>
          <th>SUBJECT NAME</th>
       </tr>
       <tr>
         <td>1</td>
         <td>19AI301</td>
         <td>PYTHON PROGRAMMING</td>
       </tr>
       <tr>
         <td>2</td>
         <td>19AI302</td>
         <TD>ENGINEERING DESIGN AND MODELING</TD>
       </tr>
       <TR>
         <TD>3</TD>
         <TD>19AI414</TD>
         <TD>FUNDAMENTALS OF WEB APPLICATION</TD>
       </TR>
       <tr>
        <td>4</td>
        <td>19CY205</td>
        <TD>PRINCIPLES OF CHEMISTRY IN ENGINEERING</TD>
       </tr>
       <TR>
         <TD>5</TD>
         <TD>19EY708</TD>
         <TD>CAREER DEVELOPMENT SKILL</TD>
       </TR>
       <TR>
         <TD>6</TD>
         <TD>19EE404</TD>
         <TD>DIGITAL ELECTRONICS</TD>
       </TR>
    </table>
</body>
</html>
```
# OUTPUT
![Screenshot 2024-11-25 213819](https://github.com/user-attachments/assets/0374b9ae-7ea8-4203-865e-02e19481834b)

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
