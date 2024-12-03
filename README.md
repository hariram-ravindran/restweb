# Ex.07 Restaurant Website
## Date:3.12.2024

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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HARI HR RESORTS AND HOTELS</title>
    <style>
        @import url('"https://fonts.googleapis.com/css2?family=Yuji+Mai&display=swap" rel="stylesheet">');

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: "Quicksand", sans-serif;
            font-optical-sizing: auto;
            font-weight: 10;
            font-style: bold;
        }

        .background {
            position: fixed;
            inset: 0;
            background-image: url("bacgrounf.jpg");
            background-size: cover;
            background-position: center;
            z-index: -1;
            filter: blur(4px);
        }

        .navbar {
            display: flex;
            justify-content: space-between;
            align-items: center;
            background-color: #FFC20D;
            padding: 10px 20px;
        }

        .navbar img{
            display: flex;
            height: 70px;
            width: 40px;
        }

        .navbar .logo {
            color: #028940;
            font-size: 3em;
            font-weight: bold;
        }

        .nav-links {
            list-style: none;
            display: flex;
            gap: 15px;
        }

        .nav-links li {
            display: inline;
            font-size: 1.5em;
        }

        .nav-links a {
            color: green;
            text-decoration: none;
            padding: 8px 15px;
            transition: background 0.3s;
        }

        .nav-links a:hover {
            background-color: #ffffffbe;
            border-radius: 4px;
        }

        .menu-container {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            padding: 20px;
            margin-top: 60px;
            justify-content: center;
        }
        https
        .card {
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            overflow: hidden;
            width: 300px;
            transition: transform 0.3s;
        }

        .card:hover {
            transform: scale(1.05);
        }

        .card img {
            width: 100%;
            height: 150px;
            object-fit: cover;
        }

        .card-content {
            padding: 15px;
            text-align: center;
        }

        .card-content h3 {
            font-size: 1.25em;
            margin-bottom: 10px;
            color: #333;
        }

        .card-content p {
            font-size: 0.9em;
            color: #777;
            margin-bottom: 10px;
        }

        .price {
            display: block;
            font-size: 1.1em;
            font-weight: bold;
            color: #e67e22;
        }
    </style>
</head>
<body>
    <div class="background"></div>

    <nav class="navbar">
        <div class="logo">HARI HR RESORTS AND HOTELS</div>
        <img src="logo.webp" alt="">
        <ul class="nav-links">
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#menu">Menu</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <div class="bg">
        <div class="menu-container">
            <div class="card">
                <img src="idly.webp" alt="IDLY">
                <div class="card-content">
                    <h3>IDLY</h3>
                    <p>“Taste the love in every bite.”</p>
                    <span class="price">Rs. 30</span>
                </div>
            </div>
            
            <div class="card">
                <img src="PANEER.jpg" alt="PANEER TIKKA">
                <div class="card-content">
                    <h3>PANEER TIKKA</h3>
                    <p>"Paneer is the energy of protein and "Barbeque ❤️🔥🔥🔥 paneer tikka paneer on fire.</p>
                    <span class="price">Rs.289</span>
                </div>
            </div>
        
            <div class="card">
                <img src="burger.jpg" alt="BURGER">
                <div class="card-content">
                    <h3>BURGER</h3>
                    <p>"Lettuce have a burgerlicious time!"</p>
                    <span class="price">Rs.328</span>
                </div>
            </div>
        </div>
        <div class="menu-container">
            <div class="card">
                <img src="choco.avif" alt="CHOCOLATE FRAPPE">
                <div class="card-content">
                    <h3>CHOCOLATE FRAPPE</h3>
                    <p>Life is brew-tiful with frappes. ...</p>
                    <span class="price">Rs.359</span>
                </div>
            </div>
            
            <div class="card">
                <img src="grill.jpg" alt="GRILL CHICKEN">
                <div class="card-content">
                    <h3>GRILL CHICKEN</h3>
                    <p>“Grilling up some serious flavor for my tummy"</p>
                    <span class="price">Rs.650</span>
                </div>
            </div>
        
            <div class="card">
                <img src="briyani.jpg" alt="BRIYANI">
                <div class="card-content">
                    <h3>BRIYANI</h3>
                    <p>Briyani is my love language. ...</p>
                    <span class="price">Rs.350</span>
                </div>
            </div>
        </div>
    </div>
    
</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot 2024-12-03 222845.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
