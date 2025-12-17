# Ex.06 Restaurant Website
## Date:17-12-2025

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
restweb1.html
<html>
    <head>
        <title>RESTAURENT</title>
        <link rel="stylesheet" href="styles.css">
    </head>
    <body>
        <div class="container">
            <div class="tab">
                <a href="restweb1.html">HOME</a>
                <a href="restweb2.html">MENU</a>
                <a href="restweb3.html">ADMIN</a>
                <a href="restweb4.html">CONTACT</a> 
            </div>
            <div class="name">
                <h1>EMPORER'S TABLE</h1>
            </div>
            <div class="chinese-quote">
                "FEEL THE TASTE OF CHINA"
            </div>
            <div class="quote">
                "Every single bite is the essence of a hundred years of culinary heritage"
            </div>
            <div class="img1">
                <img src="rest3.jpeg" width="500" height="400">
            </div>
            <footer class="copyrights">
                &copy; K Shanmuga priya-(25004352)
            </footer>
        </div>
    </body>
</html>
styles.css
.container
{
    background-image: url(rest2.jpg) ;
    height: 900px;
    width: 1800px;
    background-repeat: no-repeat;
    padding: 10px;
    padding-right: 5px;
    background-size: cover;
    border: 3px solid black ;
    margin-left: 10px;
    margin-right: 10px;
    font-family:sans-serif;
}
.tab 
{
    width: 550px;
    height: 25px;
    border: 2px solid rgb(251, 228, 228);
    padding: 10px;
    word-spacing: 70px;
    background-color: rgb(237, 110, 172);
    text-align: center;
    top: 5px;
    left: 1200px;
    position: relative;
   
}
.name
{
    color : rgb(201, 144, 215);
    font-family:'Times New Roman';
    position: relative;
    font-size: 300%;
    top: -130px;
}
.chinese-quote
{
    color: black;
    font-size: 180%;    
    top: -150px;
    position: relative;
    text-align: center;
    font-family: 'Franklin Gothic Medium';
}
.quote
{
  color: rgba(105, 15, 34, 0.796);
    font-size: 250%;
    top: -150px;
    position: relative;
    text-align: center; 
    font-family:'Lucida Sans'; 
}
.img1
{
    position: relative;
    top: -100px;
    left: 700px;
}
.copyrights
{
    width: 1820px;
    height: 17px;
    background-color: darkblue;
    position: relative;
    text-align: center;
    color: antiquewhite;
    top: 130px;
    right: 10px;
}
restweb2.html
<html>
    <head>
        <title>RESTAURENT</title>
        <link rel="stylesheet" href="style1.css">
    </head>
    <body>
        <div class="container">
            <div class="tab">
                <a href="restweb1.html">HOME</a>
                <a href="restweb2.html">MENU</a>
                <a href="restweb3.html">ADMIN</a>
                <a href="restweb4.html">CONTACT</a> 
            </div>
            <div class="name">
                <h1>MENU</h1>
            </div >
            <div class="menu">
                <div class="item">
                    <img src="chow mein.webp" width="300" height="150">
                    <h1>Chow mein</h1>
                    <p>Rs.400</p>
                </div>
                <div class="item">
                    <img src="dimsum.avif" width="300" height="150">
                    <h1>Dimsum</h1>
                    <p>Rs.200</p>
                </div>
                <div class="item">
                    <img src="hot pot.jpeg" width="300" height="150">
                    <h1>Hot pot</h1>
                    <p>Rs.700</p>
                </div>
                <div class="item">
                    <img src="mapo tofu.webp" width="300" height="150">
                    <h1>Mapo tofu</h1>
                    <p>Rs.349</p>
                </div>
                <div class="item">
                    <img src="ramen.jpeg" width="300" height="150">
                    <h1>Ramen</h1>
                    <p>Rs.370</p>
                </div>
                <div class="item">
                    <img src="rice noodles.jpg" width="300" height="150">
                    <h1>Rice noodles</h1>
                    <p>Rs.150</p>
                </div>
                <div class="item">
                    <img src="sushi.avif" width="300" height="150">
                    <h1>Sushi</h1>
                    <p>Rs.450</p>
                </div>
            </div>
         <footer class="copyrights">
                &copy; K Shanmuga priya-(25004352)
            </footer>
        </div>
    </body>
</html>
style1.css
.container
{
    background-image: url(rest2.jpg) ;
    height: 900px;
    width: 1800px;
    background-repeat: no-repeat;
    padding: 10px;
    padding-right: 5px;
    background-size: cover;
    border: 3px solid black ;
    margin-left: 10px;
    margin-right: 10px;
    font-family:monospace;
}

.tab 
{
    width: 550px;
    height: 25px;
    border: 2px solid rgb(251, 228, 228);
    padding: 10px;
    word-spacing: 70px;
    background-color: rgb(237, 110, 172);
    text-align: center;
    top: 5px;
    left: 1200px;
    position: relative;
   
}

.name 
{
    color: rgb(100, 9, 114);
    font-family: fantasy;
    text-align: left;
    position: relative;
    font-size: 300%;
    top: -120px;
}

.menu 
{
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(50px, 1fr));;
    gap: 50px;
    justify-items: center;
    padding: 10px;
    margin-top: -70px;
}

.item {
    background-color: rgb(232, 232, 174);
    border-radius: 8px;
    text-align: center;
    padding: 10px;
    width: 100%;
}

.item img {
    border-radius: 10px;
    width: 100%;
    height: 180px;
    object-fit: cover;
}

.item h1 {
    font-size: 15px;
    color: black;
    margin-top: 15px;
}

.item p {
    color: black;
    margin-bottom: 1px;
}

.copyrights
{
    width: 1820px;
    height: 17px;
    background-color: darkblue;
    position: relative;
    text-align: center;
    color: antiquewhite;
    top: 390px;
    right: 10px;
}
restweb3.html
<html>
    <head>
        <title>RESTAURENT</title>
        <link rel="stylesheet" href="stlyle2.css">
    </head>
    <body>
        <div class="container">
            <div class="tab">
                <a href="restweb1.html">HOME</a>
                <a href="restweb2.html">MENU</a>
                <a href="restweb3.html">ADMIN</a>
                <a href="restweb4.html">CONTACT</a> 
            </div>
        <div class="name">
            <h1>ADMIN</h1>
        </div>
        <div class="admin">
            <div class="admin1">
                <img src="img.png.jpg"100" height="200">
                <h1>Shanmuga priya.K</h1>
                <p >OWNER</p>
            </div>
            <div class="admin1">
                <img src="vijay.avif" width="100" height="200">
                <h1>Josheph Vijay</h1>
                <p >SENIOR MANAGER</p>
            </div>
            <div class="admin1">
                <img src="dhoni.jpg" width="100" height="200">
                <h1>M.S.Dhoni</h1>
                <p >Manager</p>
            </div>
            <div class="admin1">
                <img src="Venkatesh_Bhat.webp" width="100" height="200">
                <h1>Venkatesh bhat</h1>
                <p >CHEF</p>
            </div>
           
        </div>
        <footer class="copyrights">
                &copy; K Shanmuga priya-(25004352)
            </footer>
        </div>
    </body>
</html>
style2.css
.container
{
    background-image: url(rest2.jpg) ;
    height: 900px;
    width: 1800px;
    background-repeat: no-repeat;
    padding: 10px;
    padding-right: 5px;
    background-size: cover;
    border: 3px solid black ;
    margin-left: 10px;
    margin-right: 10px;
    font-family:monospace;
}

.tab 
{
    width: 550px;
    height: 25px;
    border: 2px solid rgb(251, 228, 228);
    padding: 10px;
    word-spacing: 70px;
    background-color: rgb(237, 110, 172);
    text-align: center;
    top: 5px;
    left: 1200px;
    position: relative;
   
}

.name 
{
    color: rgb(100, 9, 114);
    font-family: fantasy;
    text-align: left;
    position: relative;
    font-size: 300%;
    top: -120px;
}

.admin
{
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(50px, 1fr));;
    gap: 50px;
    justify-items: center;
    padding: 10px;
    margin-top: -70px;
}
.admin1
{
    background-color: rgb(255, 255, 98);
    border-radius: 10px;
    text-align: center;
    padding: 10px;
    width: 250px;
     margin-top: -50px;
    height: 250px;
    margin-right: 10px;
}

.admin1 img 
{
    border-radius: 10px;
    width: 100%;
    height: 200px;
    object-fit: cover;
    border-radius: 10px;
}

.admin1 h1 
{
    font-size: 15px;
    color: black;
    margin-top: 15px;
}

.admin1 p
 {
    color: black;
    margin-bottom: 1px;
}

.copyrights
{
    width: 1820px;
    height: 17px;
    background-color: darkblue;
    position: relative;
    text-align: center;
    color: antiquewhite;
    top: 435px;
    left:-15px; 
}
restweb4.html
<html>
    <head>
        <title>RESTAURENT</title>
        <link rel="stylesheet" href="styles3.css">
    </head>
    <body>
        <div class="container">
            <div class="tab">
                <a href="restweb1.html">HOME</a>
                <a href="restweb2.html">MENU</a>
                <a href="restweb3.html">ADMIN</a>
                <a href="restweb4.html">CONTACT</a> 
            </div>
            <div class="name">
                <h1>CONTACT</h1>
            </div>
            <div class="details">
                <h1>Visit us at:</h1>
                <p>Empire's Table<br>59,steve street<br>will road<br>India</p>
                <br>
                <h1>Phone:</h1>
                <p>+91 123 456 7890</p>
                <br>
                <h1>Email ID:</h1>
                <p>empirestable@gmail.com</p>
                </div>
            <footer class="copyrights">
                &copy; K Shanmuga priya-(25004352)
            </footer>
        </div>
    </body>
</html>
style3.css
ntainer
{
    background-image: url(rest2.jpg) ;
    height: 900px;
    width: 1800px;
    background-repeat: no-repeat;
    padding: 10px;
    padding-right: 5px;
    background-size: cover;
    border: 3px solid black ;
    margin-left: 10px;
    margin-right: 10px;
    font-family:sans-serif;
}
.tab 
{
    width: 550px;
    height: 25px;
    border: 2px solid rgb(251, 228, 228);
    padding: 10px;
    word-spacing: 70px;
    background-color: rgb(237, 110, 172);
    text-align: center;
    top: 5px;
    left: 1200px;
    position: relative;
   
}
.name
{
    color: rgb(42, 166, 112);
    font-family: fantasy;
    text-align: left;
    position: relative;
    font-size: 250%;
    top: -50px;
}

.details 
{
    color: rgb(0, 0, 0);
    position: relative;
    top: -70px;
    left: 50;
    size: 15px;
}
.copyrights
{
    width: 1820px;
    height: 17px;
    background-color: darkblue;
    position: relative;
    text-align: center;
    color: antiquewhite;
    top: 250px;
    left:-15px; 
}

```


## OUTPUT:
![alt text](<Screenshot (43).png>)
![alt text](<Screenshot (44).png>)
![alt text](<Screenshot (45).png>)
![alt text](<Screenshot (42).png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
