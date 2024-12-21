# Ex.07 Restaurant Website
## Date: 18-12-2024

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
<html>

<head>
    <style>
        .ti {
            width: 1400px;
            height: 90px;
            border: 1px;
            background-color: rgba(29, 16, 16, 0.877);
            border-radius: 50px;
            font-size: 30;
        }

        a {
            text-decoration: none;
            color: aliceblue;
        }

        li {
            display: inline-block;
            padding-top: 2%;
            padding-right: 10%;
            padding-left: 4%;
            padding-bottom: 4%;
            font-size: 30;
        }

        img {
            border-radius: 30px;
            position: relative;
            height: auto;
            width: 90%;
            margin-bottom: 2%;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #f9f9f9;
            color: #333;
        }

        .text {
            width: 80%;
        }

        h1 {
            font-size: 50;
            color: #d35400;
            text-align: center;
            margin-bottom: 2%;
        }

        p {
            font-family: 'Courier New', Courier, monospace;
            font-size: 20px;

        }
    </style>
</head>

<body>
    <br>
    <center>
        <h1>~ Paws & Plates ~</h1>
        <nav class="ti">
            <ul>
                <li><a href="Home.html" target="_self">Home</a></li>
                <li><a href="Menu.html" target="_blank">Menu</a></li>
                <li><a href="Adminstration.html" target="_blank">Adminstration</a></li>
                <li><a href="Contact.html" target="_blank">Contact Us</a></li>
            </ul>
        </nav><br><br>
        <div>
            <img src="bg1.jpg">
        </div>
        <div class="text">
            <h1>About Us</h1>
            <p>Welcome to <strong>Paws & Plates</strong>, where culinary passion meets a warm dining experience.
                Established in 2010, we have been serving mouthwatering dishes crafted with the finest ingredients.Our
                mission is to provide a place where friends, family, and food lovers can gather to enjoy authentic
                flavors and unforgettable moments.From our talented chefs to our attentive staff, we are committed to
                creating a memorable dining experience for each and every guest.</p>
        </div>

    </center>
</body>

</html>
```
```
<html>

<head>
    <style>
        ti {
            color: rgb(255, 249, 241);
            text-shadow: 4px 2px rgb(196, 164, 35);
            font-size: 80;
            font-family: Georgia, 'Times New Roman', Times, serif;
        }

        img {
            display: inline;
            width: 110px;
            height: 100px;
        }

        body {
            background-size: 100%;
            background-repeat: no-repeat;
            max-height: 700%;
        }
        hr{
            width: 240px; 
            margin-top: 0%; 
            height: 2px;
            background-color: rgb(192, 237, 250);
        }
    </style>
</head>

<body background="border.jpg">
    <br><br><br><br><br><br>
    <center>
        <pre><img src="sym1.jpg"> <ti>MENU</ti> <img src="sym1.jpg">
        <hr></pre>
    </center>
    <iframe src="frame1.html" scrolling="no" width="49.9%" height="355%" style="border: none;"></iframe>
    <iframe src="frame2.html" scrolling="no" width="49.5%" height="355%" style="border: none;"></iframe>


</body>

</html>
```
```
<html>

<head>
    <style>
        .food {
            margin-left: 20%;
            display: grid;
            grid-template-columns: 220px;
            gap: 20px;
            width: fit-content;

        }

        .food .items:hover {
            transform: scale(1.2);
            box-shadow: 0 8px 15px rgba(0, 0, 0, 0.2);
        }

        img {
            width: 180px;
            margin-left: 42%;
            margin-bottom: 2%;
        }

        .contet_wrapper {
            width: 80%;
            margin: 0 auto;
            padding: 20px;
        }

        body {
            background-repeat: no-repeat;
            background-size: cover;
        }

        .food .items {
            background: rgb(239, 239, 204);
            border: 2px;
            border-radius: 15px;
            width: 350;
            text-align: center;
            padding: 25px;
            box-shadow: 3px 5px 3px rgb(71, 65, 65);
            gap: 55px;
            font-size: 25;
            align-items: center;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        con {
            margin-left: 30%;
            text-shadow: 3px 2px rgb(196, 164, 35);
            color: aliceblue;
            font-size: 50;
            font-family: 'Courier New', Courier, monospace;
        }
    </style>
</head>

<body>
    <br><br>
    <pre><img src="tand.jpg">
        <con>TANDOORI</con></pre>
    <div class="contet_wrapper">
        <div class="food">
            <div class="items">TANDOORI CHICKEN</div>
            <div class="items">TANDOORI SHRIMP</div>
            <div class="items">TANDOORI BEEF</div>
            <div class="items">VEGGIE TANDOORI</div>
        </div>
    </div><br><br>
    <pre><img src="biri.jpg">
        <con>BIRIYANI</con></pre>
    <div class="contet_wrapper">
        <div class="food">
            <div class="items">VEGGIE BIRIYANI</div>
            <div class="items">CHICKEN BIRIYANI</div>
            <div class="items">KOLKATA BIRIYANI</div>
            <div class="items">SINDHI BIRIYANI</div>
        </div>
    </div><br><br>
    <pre><img src="kulfi.jpg">
            <con>KULFI</con></pre>
    <div class="contet_wrapper">
        <div class="food">
            <div class="items">SAFFRON KULFI</div>
            <div class="items">GULAB JAMUN</div>
            <div class="items">PISTACHIO KULFI</div>
        </div>
    </div>
</body>

</html>
```
```
<html>

<head>
    <style>
        .food {
            margin-left: 10%;
            display: grid;
            grid-template-columns: 220px;
            gap: 20px;
            width: fit-content;
        }

        .food .items {
            background: rgb(239, 239, 204);
            border: 2px;
            border-radius: 15px;
            width: 350;
            text-align: center;
            padding: 25px;
            box-shadow: 3px 5px 3px rgb(71, 65, 65);
            font-size: 25;
            align-items: center;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .contet_wrapper {
            width: 80%;
            margin: 0 auto;
            padding: 20px;
        }

        img {
            width: 180px;
            margin-left: 36%;
            margin-bottom: 2%;
        }
        .food .items:hover {
            transform: scale(1.2);
            box-shadow: 0 8px 15px rgba(0, 0, 0, 0.2);
        }
        con {
            margin-left: 5%;
            text-shadow: 3px 2px rgb(196, 164, 35);
            color: aliceblue;
            font-size: 50;
            font-family: 'Courier New', Courier, monospace;
        }

        body {
            background-repeat: no-repeat;
            background-size: cover;
            height: fit-content;
        }
    </style>
</head>

<body background=>
    <br><br>
    <pre><img src="appe.jpg">
            <con>  APPETIZERS</con></pre>
    <div class="contet_wrapper">
        <div class="food">
            <div class="items">VEGETABLE SAMOSA</div>
            <div class="items">LAMB SAMOSA</div>
            <div class="items">EGGPLANT PAKORA</div>
            <div class="items">CHICKEN PAKORA</div>
        </div>
    </div><br><br>
    <pre><img src="sides.jpg">
            <con>SIDES & BREADS</con></pre>
    <div class="contet_wrapper">
        <div class="food">
            <div class="items">MANGO PESAREL</div>
            <div class="items">BUTTER NAAN</div>
            <div class="items">GARLIC NAAN</div>
            <div class="items">KEEMA NAAN</div>
        </div>
    </div><br><br>
    <pre><img src="vege.jpg">
            <con>  VEGETABLES</con></pre>
    <div class="contet_wrapper">
        <div class="food">
            <div class="items">SAAG PANEER</div>
            <div class="items">SAAG ALOO</div>
            <div class="items">VEGGIE CURRY</div>
        </div>
    </div>
</body>

</html>
```
```
<html>

<head>
    <style>
        ti {
            color: rgb(255, 255, 255);
            text-shadow: 4px 2px 7px rgb(0, 0, 0);
            font-size: 80;
            font-family: Georgia, 'Times New Roman', Times, serif;
        }

        hr {
            width: 1100px;
            margin-top: 0%;
            height: 0.9px;
            background-color: rgb(162, 160, 160);
        }

        .con {
            width: 60%;
            margin: 20px auto;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            padding: 20px;
            background-color: rgb(255, 255, 255);
            border-radius: 10px;
            box-shadow: 20px;
            box-shadow: 0 0 15px rgb(0, 0, 0);
        }

        .staff-card {
            background-color: rgb(216, 246, 221);
            border: 1px solid black;
            border-radius: 10px;
            text-align: center;
            padding: 15px;
            box-shadow: 0 2px 5px rgb(0, 0, 0);
            transition: transform 0.2s;
        }

        .staff-card:hover {
            transform: scale(1.05);
            color: black;
        }

        .staff-card img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            object-fit: cover;
            border: 2px solid black;
        }

        .staff-card name {
            margin: 10px 0 5px;
            font-size: 1.2em;
        }

        .staff-card p {
            margin: 5px 0;
            color: black;
        }

        body {
            background-image: url("bg6.jpg");
            background-repeat: no-repeat;
            background-size: cover;

        }
    </style>
</head>

<body>
    <center>
        <ti>Restaurant Staff Administration</ti>
    </center>
    <hr><br><br><br>
    <div class="con">
        <div class="staff-card">
            <img src="a3.jpg"><br>
            <name>Augustine Hawthorne</name>
            <p>Restaurant Manager</p>
        </div>
        <div class="staff-card">
            <img src="a5.jpg"><br>
            <name>Aleksander Kings</name>
            <p>Kitchen Manager</p>
        </div>

        <div class="staff-card">
            <img src="a2.jpg"><br>
            <name>Azriel Hawke</name>
            <p>Head Chef</p>
        </div>

        <div class="staff-card">
            <img src="a1.jpg"><br>
            <name>Luca Vitiello</name>
            <p>Sous Chef</p>
        </div>

        <div class="staff-card">
            <img src="a4.jpg"><br>
            <name>Lauren Asher</name>
            <p>Senior Waiter</p>
        </div>

        <div class="staff-card">
            <img src="a6.jpg"><br>
            <name>Xavier Allister</name>
            <p>Maintiance Staff</p>
        </div>


    </div>

</body>

</html>
```
```
<html>

<head>
    <style>
        
        body{
            background-repeat: no-repeat;
            background-size: 1465px 659px;
        }
    </style>
</head>

<body background="bg7.jpg">
    <center>CONTACT US</center>

    <iframe src="cframe1.html" width="49%" height="600px" scrolling="none" style="border: none;"></iframe>
    <iframe src="cframe2.html" width="49%" height="600px" scrolling="none" style="border: none;"></iframe>

    
</body>

</html>
```
```
<html>

<head>
    <style>
        .bo {
            background-color: rgb(212, 245, 203);
            background: linear-gradient(to bottom, rgb(123, 237, 123), rgb(251, 251, 251));
            border: 2px;
            box-shadow: 2px 5px 8px;
            width: 220px;
            height: 20x;
            text-align: center;
            padding: 1%;
            border-radius: 12px;
            margin-bottom: 4%;
            margin-left: 60%;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .bo:hover{
            transform: scale(1.2);
            box-shadow: 0 8px 15px rgba(0, 0, 0, 0.2);
        }
        .top {
            margin-left: 60%;
            margin-top: 15%;
        }

        .ma {
            margin-left: 55%;
            text-shadow: 4px 3px 3px rgb(48, 116, 5);
            color: aliceblue;
            font-size: 50;
            font-family: 'Courier New', Courier, monospace;
        }
        img{
            width: 25px;
            height: 25px;
        }
    </style>
</head>

<body>
    <div class="top"></div>
    <div class="ma"><img src="lo.jpg">Location</div>
    <div class="bo">Main road,Chennai</div>
    <div class="ma"><img src="ph.jpg">Number</div>
    <div class="bo">1234567892</div>
    <div class="ma"><img src="ins.jpg">Instagram</div>
    <div class="bo">Paws_and_Plates</div>


</body>

</html>
```
```
<html>

<head>
    <style>
        .bo {
            background-color: rgb(212, 245, 203);
            background: linear-gradient(to bottom, rgb(123, 237, 123), rgb(251, 251, 251));
            border: 2px;
            box-shadow: 2px 5px 8px;
            width: 220px;
            height: 20x;
            text-align: center;
            padding: 1%;
            border-radius: 12px;
            margin-bottom: 4%;
            margin-left: 14%;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .bo:hover {
            transform: scale(1.2);
            box-shadow: 0 8px 15px rgb(1, 125, 36);
        }

        .top {
            margin-left: 60%;
            margin-top: 15%;
        }

        .ma {
            margin-left: 10%;
            text-shadow: 4px 3px 3px rgb(48, 116, 5);
            color: aliceblue;
            font-size: 50;
            font-family: 'Courier New', Courier, monospace;
        }

        img {
            width: 25px;
            height: 25px;
        }
    </style>
</head>

<body>
    <div class="top"></div>
    <div class="ma"><img src="tm.jpg">Timings</div>
    <div class="bo">9:00a.m. - 11:00 p.m.</div>
    <div class="ma"><img src="em.jpg">Email</div>
    <div class="bo">pawsandplates@gmail.com</div>
    <div class="ma"><img src="tw.jpg">Twitter</div>
    <div class="bo">Paws_and_Plates</div>

</body>

</html>
```

## OUTPUT:

![alt text](static/1.png)
![alt text](static/2.png)
![alt text](static/3.png)
![alt text](static/4.png)
![alt text](static/5.png)
![alt text](static/6.png)
![alt text](static/7.png)
![alt text](static/8.png)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
