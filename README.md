# Ex03 Time Table
## Date:04.04.2024

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
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Slot Timetable</title>
    
  </head>

  <body>
    <img
      src="logo.png" height="100" width="650"/>
    <h3 class="name">SLOT TIMETABLE - Dan Jas J (212223040028)</h3>
    <table border="1" class="table1">
      <tr class="row1" >
        <th bgcolor="pink">Day/Time</th>
        <th bgcolor="pink">Monday</th>
        <th bgcolor="pink">Tuesday</th>
        <th bgcolor="pink">Wednesday</th>
        <th bgcolor="pink">Thursday</th>
        <th bgcolor="pink">Friday</th>
        <th bgcolor="pink">Saturday</th>
      </tr>
      <tr>
        <td bgcolor="lavender">8-10</td>
        <td bgcolor="blue">FS</td>
        <td bgcolor="blue">Ethical Hacking</td>
        <td colspan="2" bgcolor="pink">FS</td>
        <td bgcolor="blue">WEB</td>
        <td bgcolor="blue">MPMC</td>
        
      </tr>
      <tr>
        <td bgcolor="lavender">10-12</td>
        <td bgcolor="pink">MPMC</td>
        <td bgcolor="pink">SPM</td>
        <td bgcolor="pink">FS</td>
        <td bgcolor="pink">SPM</td>
        <td bgcolor="pink">YOGA</td>
        <td bgcolor="pink">FS</td>
      </tr>
      <tr>
        <td bgcolor="lavender">12-1</td>
        <th colspan="6" class="x" bgcolor="beige">LUNCH BREAK</th>
      </tr>
      <tr>
        <td bgcolor="lavender">1-3</td>
        <td bgcolor="pink">DS</td>
        <td bgcolor="pink">WEB</td>
        <td bgcolor="pink">MPMC</td>
        <td bgcolor="pink">WEB</td>
        <td bgcolor="pink">AQLR</td>
        <td bgcolor="pink">ETHICAL HACKING</td>
       
      </tr>
      <tr>
        <td bgcolor="lavender">3-5</td>
        <th colspan="5" bgcolor="pink">FS</th>
        <td bgcolor="pink">DS</td>
      </tr>
    </table>
    <br />
    <br />
    <table border="1" class="table2">
      <tr>
        <th bgcolor="orange">S.No.</th>
        <th bgcolor="orange">Subject Code</th>
        <th bgcolor="orange">Subject Name</th>
      </tr>
      <tr>
        <td bgcolor="violet">1.</td>
        <td bgcolor="yellow">19EC408</td>
        <td bgcolor="yellow">Microprocessor and Microcontroller (MPMC)</td>
      </tr>
      <tr>
        <td bgcolor="violet">2.</td>
        <td bgcolor="yellow">19AI403</td>
        <td bgcolor="yellow">Introduction To DS(DS)</td>
      </tr>
      <tr>
        <td bgcolor="violet">3.</td>
        <td bgcolor="yellow">19CS417</td>
        <td bgcolor="yellow">Ethical Hacking</td>
      </tr>
      <tr>
        <td bgcolor="violet">4.</td>
        <td bgcolor="yellow">19AI414</td>
        <td bgcolor="yellow">Fundamentals of Web Applications Development (WEB)</td>
      </tr>
      <tr>
        <td bgcolor="violet">5.</td>
        <td bgcolor="yellow">19CS504</td>
        <td bgcolor="yellow">Software Project Management(SPM)</td>
      </tr>
      <tr>
        <td bgcolor="violet">6.</td>
        <td bgcolor="yellow">19EN616</td>
        <td bgcolor="yellow">Yoga And Meditation</td>
      </tr>
      <tr>
        <td bgcolor="violet">7.</td>
        <td bgcolor="yellow">19EY704</td>
        <td bgcolor="yellow">Advanced Quantitative and Logical Reasoning</td>
      </tr>
    </table>
  </body>
</html>
```

## OUTPUT

![WhatsApp Image 2024-04-04 at 21 51 35_799203b2](https://github.com/DanJas10/slot/assets/150931233/5b98b861-ed4d-4b7c-84c9-4277af99da44)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
