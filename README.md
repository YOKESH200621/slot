# Ex04 Time Table
## Date:
23/05/2025
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
        <img src="/static/logo.png">
        <table border="1" cellspacing="15" cellpadding="2">
            <caption>Timetable  NAME:Punniyakotti.M   REF.NO:212224240122</caption>
            <tr bgcolor="green">
                <th>day/time</th>
                <th>monday</th>
                <th>tuesday</th>
                <th>wednesday</th>
                <th>friday</th>
                <th>saturday</th>
            </tr>
            <tr>
                <td>8-10</td>
                <td colspan="1">EDM</td>
                <td>WEB</td>
                <td>ENGLISH</td>
                <td>MATHS</td>
                <td>WEB</td>

            </tr>
            <TR>
                <td>10-12</td>
                
                <td colspan="1">EDM</td>
                <td>WEB</td>
                <td>ENGLISH</td>
                <td>MATHS</td>
                <td>WEB</td>
                

            </TR>
            <tr>
                <td>12-1</td>
                <td colspan="6" align="center">LUNCH</td>
                


            </tr>
            <tr>
                <td>1-3</td>
                <td colspan="1">EDM</td>
                <td>WEB</td>
                <td>ENGLISH</td>
                <td>MATHS</td>
                <td>WEB</td>


            </tr>
            <tr>
                <td>3-5</td>
                <td colspan="1">EDM</td>
                <td>WEB</td>
                <td>ENGLISH</td>
                <td>MATHS</td>
                <td>WEB</td>

            </tr>
          
    
            
                







        </table>





        <table border="1" cellspacing="15" cellpadding="2">
        <caption>Timetable  NAME:Punniyakotti    REF.NO:212224240122</caption>
        <tr>
            <td>s.no</td>
            <td>subject code</td>
            <td colspan="4" align="center">subject name </td>
        </tr>
        <tr>
            <th>1</th>
            <th colspan="2">19AI414</th>
            <th colspan="3">fundamental of web application development(FWAD)</th>
        </tr>
        <tr>
            <th>2</th>
            <th colspan="2">19EN612</th>
            <th colspan="3">german basic(GER)</th>
        </tr>
        <tr>
            <th>3</th>
            <th colspan="2">19PH206</th>
            <th colspan="3">physics for information technology(PHY)</th>
        </tr>
        <tr>
            <th>4</th>
            <th colspan="2">19CY205</th>
            <th colspan="3">principles of chemistry in engineering(CHE)</th>
        </tr>
        <tr>
            <th>5</th>
            <th colspan="2">19MA201</th>
            <th colspan="3">calculus and matrix algebra(MAT)</th>
        </tr>
        <tr>
            <th>6</th>
            <th colspan="2">19EY701</th>
            <th colspan="3">soft skills(SS)</th>
        </tr>
        
        
        
    
    </table>
    </body>
</html>

```
## OUTPUT
![terminal](https://github.com/user-attachments/assets/4e14f828-8c9c-4425-b041-e60babac3b26)
![xep](https://github.com/user-attachments/assets/ab0e5409-1ade-4ba6-a864-7cd60b0a4316)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
