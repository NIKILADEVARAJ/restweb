# Ex.07 Restaurant Website
## Date:13/12/2024

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
rest.html

<!DOCTYPE html>
<html lang="en">
<head>
    <link rel="stylesheet" href="rest.css">
</head>
<body>
    <div align="center" id="resaturant">

        <img src="hotel.jpg" height="650" width="900" >
        <a href="wave.html" id="tag" >WAVES</a>
        <a href="order.html" id="order">ORDER NOW </a>
        <a href="contact.html" id="contact">CONTACT US</a>
        <a href="administration.html" id="offers">ADMINISTRATION</a>
    </div>
    <footer align="center" id="copywrite">
        Designed and devloped by Nikila &copy 2024
    </footer>
</body>
</html>

order.html
<!DOCTYPE html>
<html lang="en">
<head>
    <style>
        body{
            background-color:chocolate;
        }
         
        img
        {
                margin-top: 100px;
                height: 250px;
                width: 250px;
                margin-left: 25px;

        } 
        
    </style>
</head>
<body>
    <div id="body">
    <h1 align="center">Order Now</h1>
    <div>
        <table>
            <tr>
        <td><img src="naan.webp"><h1>NAAN</h1></td>
        <td><img src="thiramisu.png"><h1>THIRAMISU</h1></td>
        <td><img src="mutton briyani.jpg"><h1>MUTTON BRIYANI</h1></td>
        <td><img src="cauliflower.jpg"><h1>CAULIFLOWER CHILLI</h1></td>
        <td><img src="ramen.jpg"><h1>RAMEN</h1></td>
    </tr>
    </table>
    </div>
    </div>
</body>
</html

contact.html
<!DOCTYPE html>
<html lang="en">
<head>
    <style>
        .image-container{
            width:40%;
            height: 70%;
        }
        .centered-text{
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%,-50%);
            font-size: x-large;
            font-weight: 500;
            background-color: darkred;
        }
        
    </style>
    <body>
        <div class="image-container">
            <img src="contact.jpg">
        </div>
    <div class="centered-text">
     <center>
   <h1> CONTACT US </h1>
</center>
    <b>phone no: 8838512605 | email -"waves@gamil.com"|<br>
        waves hotels Pvt Ltd.,<br>
        no,25/30,Fourth floor,<br>
        ramky house , chennai 604206</b>
    </div>
    </body> 
</head>

wave.html
<!DOCTYPE html>
<html lang="en">
<head>
    <style>
        pre{
            padding: 25px;
            font-size: large;
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
            
        }
       #order
        {
                display: inline;
                margin-left: 10px;
                color:chocolate;
        }
        #h
        {
            text-align: center;
            font-style:inherit;
            margin-top: 10px;
            padding: 25px;
            position: relative;
            top: 50px;
            left: 0px;
            background-color:aqua;
        }
        body
        {
            background-color:darksalmon;

        }
    </style>
</head>
<body >
    
    <h1 id="h">ABOUT US</h1>
    <pre>
        

<b>WELCOME TO WAVES!</b>

<i>WAVES Restaurant  is a restaurant chain that operates primarily in the Indian state of Tamil Nadu.</i>

<b>What's special about as?</b>
<i>The first outlet was opened in 1957 at SAN FRANSICO.
Since then, it operates with over 101 outlets globally with 92 outlets in India, and 9 outlets overseas</i>

<b>What we focus on?</b>
 <i>The Thalappakatti restaurants focus on indian menu's as the core product.</i>
    </pre>

</body>
</html>

rest.css
*{
    margin: 0px;
    padding: 0px;
}

#template
{
    align-items: center;
    width: 100%;
    object-fit: cover;
    /* height: 800px; */
}
#tag
{
    position: absolute;
    top:40px;
    left: 250px;
    text-decoration: none;
    color:cyan;
    font-weight: 400;
    color: orange;
    text-transform: capitalize;
    font-size: 40px;
    
}
#order
{
    position: absolute;
    top:50px;
    left: 420px;
    text-decoration: none;
    color: cyan;
    font-weight: 400;
    font-size: 30px;
}
#contact
{
    position: absolute;
    top:50px;
    left: 625px;
    text-decoration: none;
    color: cyan;
    font-weight: 400;
    font-size: 30px; 
}
#offers
{
    position: absolute;
    top:50px;
    left: 850px;
    text-decoration: none;
    color:cyan;
    font-weight: 400;
    font-size: 30px;   
}
#copywrite
{
    color:black;
    font-size: large;
}

administration.html
<html lang="en">
<head>
    <style>
        body
        {
            background-color: rgba(255, 60, 0, 0.733);
        }
        #container
        {
            background-color: whitesmoke;
            display: flex;
            border: 5px solid aquamarine;
            height: 500px;
            width: auto;
            justify-content: space-evenly;
            
        }
        #main
        {
            border: 1px solid black;
        }
        .box
        {
            position: relative;
            display: inline-block;
            top: 150px;
            height: 200px;
            width: 200px;
            border: 2px solid black;
            background-color: pink;
            
        }
        #title
        {
            text-align: center;
            font-size: 50px;
            font-family:Georgia, 'Times New Roman', Times, serif;
            font-weight: 700;
            background-size:cover ;
        }
        
        #chef1
        {
            position: absolute;
            bottom: 170px;
            left: 100px;
            font-weight: 600;
            font-size: large;
            font-style:italic;
        }
        #chef2
        {
            position: absolute;
            bottom: 170px;
            left: 370px;
            font-weight: 600;
            font-size: large;
            font-style: italic;
        }
        #chef3
        {
            position: absolute;
            bottom: 170px;
            left: 600px;
            font-weight: 600;
            font-size: large;
            font-style: italic;
        }
        #chef4
        {
            position: absolute;
            bottom: 170px;
            left: 900px;
            font-weight: 600;
            font-size: large;
            font-style: italic;
        }
        #chef5
        {
            position: absolute;
            bottom: 170px;
            left: 1150px;
            font-weight: 600;
            font-size: large;
            font-style:italic;
        }
    </style>
    
</head>
<body>
    <div align="center" id="title">Head Chef</div>
    <div id="container">

            <div ><img src="chef 5.jpg" alt="" class="box"></div>
            <div ><img src="chef 2.jpg" alt="" class="box"></div>
            <div ><img src="chef 3.jpg" alt="" class="box"></div>
            <div ><img src="chef 4.webp" alt="" class="box"></div>
            <div ><img src="chef 1.jpg" alt="" class="box"></div>

    </div>
    <p id="chef1">NILAN </p> 
        <p id="chef2">VITHYA SANKAR</p>
         <p id="chef3">HARISH ANTO</p>
        <p id="chef4">KEERTHY</p>  
        <p id="chef5">DAMU</p>
</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot (97)-1.png>)
![alt text](<Screenshot (95).png>)
![alt text](<Screenshot (93).png>)
![alt text](<Screenshot (91).png>)
![alt text](<Screenshot (99).png>)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
