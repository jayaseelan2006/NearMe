# Ex04 Places Around Me
## Date: 

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
'''
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>




<script>

    function coordinate(event) { 
        let x = event.clientX;
        let y = event.clientY;
        document.getElementById("text1").value = x;
        document.getElementById("text2").value = y;
    }

</script>
    

<body>
     
    <h1><b>IT COMPANY <b></h1>
    
<img src="map1.png" width="1000px" usemap="#MapNew" onmousemove="coordinate (event)"> <br>

<MAP name="MapNew">
    
    <AREA shape="RECT" coords="730,270,880,310" href="https://eagletechitsolutions.com/" Title="Eagle Tech It Solutions Chennai">
    
    <AREA shape="RECT" coords="563,318,735,360" href="https://www.telliant.com/" Title="Telliant Systems India Private Limited">
    
    <AREA shape="RECT" coords="567,136,730,182" href="https://htssindia.in/#/" Title="HI - Tech Company Software Solutions (Chennai) Pvt. Ltd.">
    
    <AREA shape="RECT" coords="468,204,592,240" href="https://deforay.com/" Title="Deforay Technologies Private Limited">
    
    <area shape="RECT" coords="387,81,531,125" href="https://www.excelanto.com/" title="Excelanto Cloud Systems Pvt Ltd">

</MAP> 
X Co-ordinate <input type="text" name="" id="text1">
Y Co-ordinate <input type="text" name="" id="text2">
</MAP>
</body>
</html>

``'

## OUTPUT
![alt text](map1.png)
![alt text](img1.png)
![alt text](img2.png)
![alt text](img3.png)
![alt text](img4.png)
![alt text](img5.png)




## RESULT
The program for implementing image maps using HTML is executed successfully.
