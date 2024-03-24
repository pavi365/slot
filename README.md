# Ex03 Time Table
## Date:24-03-24

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
              <title> web </title>
     </head>
     <body bgcolor="white" TEXT="black">
<center>
     <img src="logo.png" width="800" align="center" /></center>
          
          <table border= "5"cellspacing="5px" cellpadding="10px" bgcolor="white" align="center">
          <CAPTION align=“top”><h3>SLOT TIME TABLE - PAVITHRA (212221220037)</h3> </CAPTION>
          
               <tr> 
               <th bgcolor="#d279a4">   DAY/TIME </th>
               <th bgcolor="#728FCE">   MONDAY </th>
               <th bgcolor="#728FCE">   TUESDAY </th>
               <th bgcolor="#728FCE">   WEDNESDAY </th>
               <th bgcolor="#728FCE">   THURSDAY </th>
               <th bgcolor="#728FCE">   FRIDAY </th>
               </tr>
               <tr>
                <th bgcolor="#728FCE"> 8-10 </th>
                <td bgcolor=" #e6b3cc"> FWAD </td>
                <td bgcolor=" #e6b3cc"> BSM </td>
                  <td bgcolor=" #e6b3cc"> FREE SLOT </td>
                <td bgcolor=" #e6b3cc"> FREE SLOT </td>
                <td bgcolor=" #e6b3cc"> COMPANY SPECIFIC </td>
               </tr>
               <tr>
                <th bgcolor="#728FCE"> 10-12 </th>
                <td bgcolor=" #e6b3cc"> FREE SLOT</td>
                <td bgcolor=" #e6b3cc"> OPEN SOURCE OS </td>
                <td bgcolor=" #e6b3cc"> BSM </td>
                <td bgcolor=" #e6b3cc"> OPEN SOURCE OS </td>
                <td bgcolor=" #e6b3cc"> FREE SLOT </td>
               </tr>
               <tr>
                <th bgcolor="#728FCE"> 12-1 </th>
                 <td colspan="5" align="center" bgcolor="#d279a4">LUNCH TIME</td>
               </tr>
               <tr>
                <th bgcolor="#728FCE"> 1-3 </th>
                <td bgcolor=" #e6b3cc"> DATA STRUCTURES </td>
                <td bgcolor=" #e6b3cc"> GENDER SENSITIZATION </td>
                <td bgcolor=" #e6b3cc"> DATA STRUCTURES </td>
                <td bgcolor=" #e6b3cc"> FWAD</td>
                <td bgcolor=" #e6b3cc">FWAD </td>
               </tr>
               
              
              <tr>
               <th bgcolor="#728FCE"> 3-5 </th>
               <td bgcolor=" #e6b3cc"> FREE SLOT </td>
               <td bgcolor=" #e6b3cc"> ADC </td>
               <td bgcolor=" #e6b3cc"> ADC</td> 
               <td bgcolor=" #e6b3cc"> FREE SLOT </td> 
               <td bgcolor=" #e6b3cc"> FREE SLOT </td>
              </tr>
           </table>
           <br>
            <table border="5px" cellpadding="10px"  align="center" >
           <tr>
           <th bgcolor="#d9ff66"> S.No </th>
             <th bgcolor=" #d9b38c"> SUBJECT CODE </th>
           <th bgcolor="#d9b38c"> SUBJECT NAME </th>
           </tr>
           <tr> 
           <td bgcolor=" #d9b38c"> 1. </td>
           <td bgcolor="#d9ff66"> 19AI414 </td>
           <td bgcolor=" #d9ff66"> Fundamental of web application and development </td>
           </tr>
           <tr>
           <td bgcolor=" #d9b38c"> 2. </td>
           <td bgcolor=" #d9ff66">19IT405</td>
           <td bgcolor=" #d9ff66">  Data structures using python  </td>
           </tr>
           <tr>
           <td bgcolor=" #d9b38c"> 3. </td>
           <td bgcolor=" #d9ff66"> 19MD601</td> 
           <td bgcolor=" #d9ff66">Biomedical Sensors and Measurements  </td>
           </tr>
           <tr>
           <td bgcolor=" #d9b38c"> 4. </td>
           <td bgcolor=" #d9ff66"> 19CS545 </td>
           <td bgcolor=" #d9ff66"> Open Source Operating System </td>
           </tr>
           <tr>
           <td bgcolor=" #d9b38c"> 5. </td>
           <td bgcolor=" #d9ff66"> 19EN609 </td>
           <td bgcolor=" #d9ff66"> Gender Sensitization </td>
           </tr>
           <tr>
           <td bgcolor=" #d9b38c"> 6. </td>
           <td bgcolor="#d9ff66"> 19EC306 </td>
           <td bgcolor=" #d9ff66"> Analog and Digital Communication </td>
           </tr>
           </table>
              
        </body>
</html> 
```


## OUTPUT
![alt text](<Screenshot 2024-03-24 183330.png>)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
