# Ex.07 Restaurant Website
## Date:14/12/2024

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
home.html

<!DOCTYPE html>
<html lang="en">
<head>
    <link rel="stylesheet" href="rest.css">
</head>
<style>
        body {
            background-image: url('WhatsApp Image 2024-12-13 at 21.36.56_4312190f.jpg');
            background-size: cover;
            background-position: center;
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
        }
        h1{
           text-align: center;
           color:white;

        }
        footer{
            color:white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
            
        }
</style>
<body>

    <header>
        <h1>Welcome to Our Restaurant</h1>
    </header> 

    <centre>
        <h1><b>THE SPICE DELIGHT</b></h1>
    </centre>
    <footer>
        <p>&copy; 2024 Restaurant Name. All rights reserved.</p>
    </footer>
</body>

</html>

rest.html

<!DOCTYPE html>
<html lang="en">
<head>
    <style>
        body {
            background-image: url('WhatsApp Image 2024-12-13 at 21.36.56_4312190f.jpg');
            background-size: cover;
            background-position: center;
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
        }

        .tag {
            display: flex;
            justify-content: center;
            gap: 20px;
            padding: 20px;
            background-color: rgba(0, 0, 0, 0.5); /* Semi-transparent background for navigation */
        }

        .tag a {
            color: white;
            text-decoration: none;
            font-size: 18px;
        }

        .tag a:hover {
            color: #ff6600;
            text-decoration: underline;
        }

        footer {
            text-align: center;
            color: white;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
            background-color: rgba(0, 0, 0, 0.7); /* Semi-transparent footer */
        }
       
    </style>
</head>
<body>

    <div class="tag">
        <a href="home.html">Home</a>
        <a href="menu.html">Order Now</a>
        <a href="administration.html">Administration</a>
        <a href="contact.html">Contact</a>
    </div>

    <footer>
        Designed and developed by Sindhuja &copy; 2024
    </footer>
</body>
</html>

menu.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant - Menu</title>
    <style>
        body { 
            font-family: Arial, sans-serif; 
            margin: 0; 
            padding: 0; 
            background-color: #f4f4f4; 
        }
        header { 
            background-color: #333; 
            color: white; 
            padding: 20px; 
            text-align: center; 
        }
        h1 { margin: 0; }
        nav { 
            text-align: center; 
            background-color: #444; 
            padding: 10px 0; 
        }
        nav a { 
            color: white; 
            padding: 10px 20px; 
            text-decoration: none; 
            margin: 0 10px; 
        }
        nav a:hover { 
            background-color: #333; 
        }
        .menu-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            margin: 20px 0;
        }
        .menu-item {
            background-color: white;
            padding: 20px;
            margin: 10px;
            text-align: center;
            border: 1px solid #ddd;
            width: 250px; /* Fixed width for uniformity */
            height: auto;
        }
        .menu-item img {
            width: 100%; /* Ensure images take the full width of the box */
            height: auto; /* Maintain aspect ratio */
            border-radius: 8px; /* Optional: Add rounded corners to images */
        }
        footer { 
            background-color: #333; 
            color: white; 
            padding: 10px; 
            text-align: center; 
        }
        /* Responsive styles */
        @media (max-width: 768px) {
            .menu-item {
                width: 100%; /* Full width for smaller screens */
                margin: 10px 0;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Our Menu</h1>
    </header>
   
    <div class="menu-container">
        <div class="menu-item">
            <img src="chapp.jpg" alt="Chappathi">
            <h3>Chappathi</h3>
            <p>Healthy food</p>
            <p>$12</p>
        </div>

        <div class="menu-item">
            <img src="noo.jpg" alt="Noodles">
            <h3>Noodles</h3>
            <p>$15</p>
        </div>

        <div class="menu-item">
            <img src="pane.jpg" alt="Paneer">
            <h3>Paneer</h3>
            <p>$10</p>
        </div>

        <div class="menu-item">
            <img src="paro.jpg" alt="Parotta">
            <h3>Parotta</h3>
            <p>$10</p>
        </div>

        <div class="menu-item">
            <img src="rice.jpg" alt="Rice">
            <h3>Rice</h3>
            <p>$10</p>
        </div>

        <div class="menu-item">
            <img src="sam.jpg" alt="Samosa">
            <h3>Samosa</h3>
            <p>$8</p>
        </div>

        <div class="menu-item">
            <img src="ros.jpg" alt="Rosemilk">
            <h3>Rosemilk</h3>
            <p>$5</p>
        </div>

        <div class="menu-item">
            <img src="ice.jpg" alt="Ice Cream">
            <h3>Ice Cream</h3>
            <p>$3</p>
        </div>

        <div class="menu-item">
            <img src="sha.jpg" alt="Shawarma">
            <h3>Shawarma</h3>
            <p>$5</p>
        </div>

        <div class="menu-item">
            <img src="vegi.jpg" alt="Vegi Rice">
            <h3>Vegi Rice</h3>
            <p>$6</p>
        </div>

        <div class="menu-item">
            <img src="fry.jpg" alt="Fried Rice">
            <h3>Fried Rice</h3>
            <p>$5</p>
        </div>

        <div class="menu-item">
            <img src="alu.jpg" alt="Aalu Parotta">
            <h3>Aalu Parotta</h3>
            <p>$8</p>
        </div>
    </div>

    <footer>
        <p>&copy; 2024 Restaurant Name. All rights reserved.</p>
    </footer>
</body>
</html>

administration.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant - Administration</title>
    <style>
        body { 
            font-family: Arial, sans-serif; 
            margin: 0; 
            padding: 0; 
            background-color: #f4f4f4; 
        }
        header { 
            background-color: #333; 
            color: white; 
            padding: 20px; 
            text-align: center; 
        }
        h1 { margin: 0; }
        nav { 
            text-align: center; 
            background-color: #444; 
            padding: 10px 0; 
        }
        nav a { 
            color: white; 
            padding: 10px 20px; 
            text-decoration: none; 
            margin: 0 10px; 
        }
        nav a:hover { 
            background-color: #333; 
        }
        footer { 
            background-color: #333; 
            color: white; 
            padding: 10px; 
            text-align: center; 
        }
        .content {
            background-color: white; 
            padding: 20px; 
            margin: 10px; 
            text-align: center; 
            border: 1px solid #ddd;
            display: inline-block;
            width: 220px; /* Fixed width for consistency */
            margin-bottom: 20px; /* Space between items */
        }
        .content img {
            width: 150px; /* Resize the image */
            height: auto; /* Maintain aspect ratio */
            border-radius: 8px; /* Optional: Adds rounded corners to the image */
        }
        .content p {
            margin-top: 10px; /* Space between the image and the name */
            font-size: 18px; /* Adjust the text size */
            font-weight: bold; /* Make the text bold */
        }
        /* Ensuring the content aligns properly in smaller screens */
        @media (max-width: 768px) {
            .content {
                width: 100%; /* Full width for smaller screens */
                margin: 10px 0;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Administration</h1>
    </header>

    <div class="content">
        <img src="sindhu.jpg" alt="admin">
        <p>Sindhuja</p>
    </div>

    <div class="content">
        <img src="chf1.jpg" alt="chef">
        <p>Santhosh</p>
    </div>

    <div class="content">
        <img src="chf2.jpg" alt="chef">
        <p>Nithya</p>
    </div>

    <div class="content">
        <img src="chf3.jpg" alt="chef">
        <p>Maha</p>
    </div>

    <div class="content">
        <img src="chf4.jpg" alt="chef">
        <p>Gowtham</p>
    </div>

    <div class="content">
        <img src="chf5.jpg" alt="chef">
        <p>Dev Adhik</p>
    </div>

    <footer>
        <p>&copy; 2024 Restaurant Name. All rights reserved.</p>
    </footer>
</body>
</html>

contact.html
<!DOCTYPE html>
<html lang="en">
<head>
    <div id="contact">
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: #f4f4f4; }
        header { background-color: #333; color: white; padding: 20px; text-align: center; }
        h1 { margin: 0; }
        nav { text-align: center; background-color: #444; padding: 10px 0; }
        nav a { color: white; padding: 10px 20px; text-decoration: none; margin: 0 10px; }
        nav a:hover { background-color: #333; }
        footer { background-color: #333; color: white; padding: 10px; text-align: center; }
        div{text-align: center;}
    </style>
    </div>
</head>
<body>
    <header>
        <h1>Contact Us</h1>
    </header>
    
    <div class="content">
        <h2>Get in Touch</h2>
        <p>Email: restaurant@example.com</p>
        <p>Phone: 123-456-7890</p>
    </div>
    <footer>
        <p>&copy; 2024 Restaurant Name. All rights reserved.</p>
    </footer>
</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot (23).png>)
![alt text](<Screenshot (24).png>)
![alt text](<Screenshot (25).png>)
![alt text](<Screenshot (26).png>)
![alt text](<Screenshot (27).png>)
![alt text](<Screenshot (28).png>)
![alt text](<Screenshot (29).png>)



## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
