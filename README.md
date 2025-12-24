# Ex.07 Restaurant Website
# Date:
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
restaurant.html
```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Summer House Eatery</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background: #f5f5f5;
            color: #333;
        }

        header {
            background: #f1e1c1;
            padding: 10px;
            text-align: center;
        }

        header h1 {
            font-size: 22px;
            margin: 5px 0;
        }

        header p {
            font-size: 14px;
            margin: 0;
        }

        nav {
            background: #4a3f35;
            padding: 8px;
            text-align: center;
        }

        nav a {
            color: white;
            margin: 0 12px;
            text-decoration: none;
            font-size: 14px;
        }

        .container {
            max-width: 1000px;
            margin: 20px auto;
            padding: 10px;
        }

        .hero img {
            width: 100%;
            height:300px;          
            object-fit: cover;          
            display: block;
        }

        .content {
            background: white;
            padding: 20px;
            margin-top: 20px;
        }

        .content h2 {
            text-align: center;
            font-size: 20px;
            margin-bottom: 10px;
        }

        .content p {
            font-size: 14px;
            line-height: 1.6;
            text-align: justify;
        }

        footer {
            text-align: center;
            padding: 10px;
            background: #4a3f35;
            color: white;
            font-size: 13px;
            margin-top: 20px;
        }
    </style>
</head>

<body>

    <header>
        <h1>The Summer House Eatery</h1>
        <p>A cozy retreat for soulful cuisine</p>
    </header>

    <nav>
        <a href="Restaurant.html">Home</a>
        <a href="Menu.html">Menu</a>
        <a href="administration.html">Staff</a>
        <a href="Contact.html">Contact</a>
    </nav>

    <div class="container">

        <div class="hero">
            <img src="restaurant.jpg" alt="Restaurant Banner">
        </div>

        <div class="content">
            <h2>Welcome to The Summer House Eatery</h2>
            <p>
                At The Summer House Eatery, we focus on fresh ingredients and simple cooking
                that brings comfort and taste together. Our menu changes with the season,
                offering dishes prepared with care and balance.
                <br><br>
                We also serve a selection of refreshing beverages including classic wines
                and handcrafted drinks that pair well with our food.
                <br><br>
                For groups of seven or more, we provide a set menu that highlights our
                popular and chef-recommended dishes.
            </p>
        </div>

    </div>

    <footer>
        <p>&copy; 2021 The Summer House Eatery</p>
    </footer>

</body>

</html>
```
menu.html
```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Summer House Eatery - Menu</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            background: #f2f2f2;
            margin: 0;
            color: #333;
        }

        header {
            background: #e6d3a3;
            text-align: center;
            padding: 10px;
        }

        header h1 {
            margin: 5px 0;
            font-size: 22px;
        }

        header p {
            margin: 0;
            font-size: 14px;
        }

        nav {
            background: #4a3f35;
            text-align: center;
            padding: 8px;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 12px;
            font-size: 14px;
        }

        .container {
            max-width: 1100px;
            margin: 20px auto;
            padding: 10px;
        }

      
        .menu-grid {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 15px;
        }

        .item {
            background: white;
            border: 1px solid #ccc;
            padding: 10px;
            text-align: center;
        }

        .item img {
            width: 150px;
            height: 150px;
            object-fit: cover;
        }

        .item h3 {
            font-size: 15px;
            margin: 8px 0 0;
        }

        footer {
            background: #4a3f35;
            color: white;
            text-align: center;
            padding: 10px;
            font-size: 13px;
            margin-top: 20px;
        }
    </style>
</head>

<body>

    <header>
        <h1>The Summer House Eatery</h1>
        <p>Curated Flavors - Crafted Fresh</p>
    </header>

    <nav>
        <a href="Restaurant.html">Home</a>
        <a href="Menu.html">Menu</a>
        <a href="administration.html">Staff</a>
        <a href="Contact.html">Contact</a>
    </nav>

    <div class="container">
        <div class="menu-grid">

            <div class="item">
                <img src="korean_fried_chicken.webp" alt="Korean Fried Chicken">
                <h3>Korean Fried Chicken</h3>
            </div>

            <div class="item">
                <img src="Tiramisu Delight.webp" alt="Tiramisu Delight">
                <h3>Tiramisu Delight</h3>
            </div>

            <div class="item">
                <img src="vietnamese coffee.webp" alt="Vietnamese Coffee">
                <h3>Vietnamese Coffee</h3>
            </div>

            <div class="item">
                <img src="mushroom ravioli.webp" alt="Mushroom Ravioli">
                <h3>Mushroom Ravioli</h3>
            </div>

            <div class="item">
                <img src="white wine sauce pasta.webp" alt="White Wine Sauce Pasta">
                <h3>White Wine Sauce Pasta</h3>
            </div>

            <div class="item">
                <img src="truffle oil drizzle.webp" alt="Truffle Oil Drizzle">
                <h3>Truffle Oil Drizzle</h3>
            </div>

            <div class="item">
                <img src="mango chilli mojito.webp" alt="Mango Chilli Mojito">
                <h3>Mango Chilli Mojito</h3>
            </div>

            <div class="item">
                <img src="nutella crepe.webp" alt="Nutella Crepe">
                <h3>Nutella Crêpe</h3>
            </div>

            <div class="item">
                <img src="cream of truffle mushroom.webp" alt="Cream of Truffle Mushroom">
                <h3>Cream of Truffle Mushroom</h3>
            </div>

            <div class="item">
                <img src="pumpkin soup.jpg" alt="Pumpkin Soup">
                <h3>Pumpkin Soup</h3>
            </div>

            <div class="item">
                <img src="truffle fries.webp" alt="Truffle Fries">
                <h3>Truffle Fries</h3>
            </div>

            <div class="item">
                <img src="cold coffee.webp" alt="Cold Coffee">
                <h3>Cold Coffee</h3>
            </div>

        </div>
    </div>

    <footer>
        <p>&copy; 2021 The Summer House Eatery</p>
    </footer>

</body>

</html>
```
administration.html
```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Summer House Eatery - Administration</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background: #f2f2f2;
            color: #333;
        }

        header {
            background: #e6d3a3;
            text-align: center;
            padding: 10px;
        }

        header h1 {
            margin: 5px 0;
            font-size: 22px;
        }

        header p {
            margin: 0;
            font-size: 14px;
        }

        nav {
            background: #4a3f35;
            padding: 8px;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 12px;
            font-size: 14px;
        }

        .container {
            max-width: 1000px;
            margin: 20px auto;
            padding: 10px;
        }

        .container h2 {
            text-align: center;
            font-size: 20px;
            margin-bottom: 20px;
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 15px;
        }

        .card {
            background: white;
            border: 1px solid #ccc;
            padding: 15px;
            text-align: center;
        }

        .card img {
            width: 120px;
            height: 120px;
            object-fit: cover;
            margin-bottom: 10px;
        }

        .card h3 {
            margin: 5px 0;
            font-size: 15px;
        }

        .card p {
            margin: 0;
            font-size: 14px;
        }

        footer {
            background: #4a3f35;
            color: white;
            text-align: center;
            padding: 10px;
            font-size: 13px;
            margin-top: 20px;
        }
    </style>
</head>

<body>

    <header>
        <h1>The Summer House Eatery</h1>
        <p>Meet the people behind our kitchen</p>
    </header>

    <nav>
        <a href="Restaurant.html">Home</a>
        <a href="Menu.html">Menu</a>
        <a href="administration.html">Staff</a>
        <a href="Contact.html">Contact</a>
    </nav>

    <div class="container">
        <h2>Our Administration Team</h2>

        <div class="grid">

            <div class="card">
                <img src="staff1.jpg" alt="Steve">
                <h3>Robert</h3>
                <p>Head Chef</p>
            </div>

            <div class="card">
                <img src="staff2.png" alt="Robert">
                <h3>Francis</h3>
                <p>Restaurant Manager</p>
            </div>

            <div class="card">
                <img src="staff3.jpg" alt="Rounak Singh">
                <h3>Steve</h3>
                <p>Executive Chef</p>
            </div>

            <div class="card">
                <img src="staff4.jpg" alt="Farhaan Thayyib">
                <h3>Joseph</h3>
                <p>Operations Staff</p>
            </div>

            <div class="card">
                <img src="staff5.jpg" alt="Santhosh">
                <h3>Chris Eves</h3>
                <p>Senior Sous Chef</p>
            </div>

            <div class="card">
                <img src="staff6.jpg" alt="Hari">
                <h3>Tom</h3>
                <p>Customer Relations Lead</p>
            </div>

        </div>
    </div>

    <footer>
        <p>&copy; 2021 The Summer House Eatery</p>
    </footer>

</body>

</html>
```
contact.html
```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Summer House Eatery - Contact</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background: #f2f2f2;
            color: #333;
        }

        header {
            background: #e6d3a3;
            text-align: center;
            padding: 10px;
        }

        header h1 {
            margin: 5px 0;
            font-size: 22px;
        }

        header p {
            margin: 0;
            font-size: 14px;
        }

        nav {
            background: #4a3f35;
            padding: 8px;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 12px;
            font-size: 14px;
        }

        .container {
            max-width: 800px;
            margin: 20px auto;
            background: white;
            padding: 20px;
            border: 1px solid #ccc;
        }

        .container h2 {
            text-align: center;
            font-size: 20px;
            margin-bottom: 15px;
        }

        .contact-info {
            font-size: 14px;
            line-height: 1.6;
        }

        .contact-info p {
            margin: 12px 0;
        }

        footer {
            background: #4a3f35;
            color: white;
            text-align: center;
            padding: 10px;
            font-size: 13px;
            margin-top: 20px;
        }
    </style>
</head>

<body>

    <header>
        <h1>The Summer House Eatery</h1>
        <p>Your cozy corner for comfort & flavors</p>
    </header>

    <nav>
        <a href="Restaurant.html">Home</a>
        <a href="Menu.html">Menu</a>
        <a href="administration.html">Staff</a>
        <a href="Contact.html">Contact</a>
    </nav>

    <div class="container">
        <h2>Contact Us</h2>

        <div class="contact-info">
            <p><strong>Address:</strong><br>
                5B, Ramachandra Ave, Lubdhi Colony,<br>
                Alwarpet, Chennai, Tamil Nadu 600018
            </p>

            <p><strong>Email:</strong><br>
                support@thesummerhouseeatery.com
            </p>

            <p><strong>Phone:</strong><br>
                +91 98765 43210
            </p>
        </div>
    </div>

    <footer>
        <p>&copy; 2021 The Summer House Eatery</p>
    </footer>

</body>

</html>
```
# OUTPUT:
<img width="1356" height="708" alt="screencapture-127-0-0-1-5501-Restaurant-html-2025-12-24-10_27_04" src="https://github.com/user-attachments/assets/f975a417-3fe8-4313-a336-dfea6c80d609" />

<img width="1356" height="770" alt="screencapture-127-0-0-1-5501-Menu-html-2025-12-24-10_26_54" src="https://github.com/user-attachments/assets/f38e181d-b309-46e1-bd6c-0ffba0e778c7" />


<img width="1356" height="644" alt="screencapture-127-0-0-1-5501-administration-html-2025-12-24-10_27_27" src="https://github.com/user-attachments/assets/20bf6465-f11b-43ba-8938-829ceb01e141" />

<img width="1365" height="767" alt="Screenshot 2025-12-24 102743" src="https://github.com/user-attachments/assets/4146fdb6-65c5-4d8b-947c-fb8ce2c4f0f8" />

# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
