# Ex.07 Restaurant Website
## Date: 02-05-25

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
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Foodie Hub</title>
    <link rel="stylesheet" href="styles.css" type="text/css">

</head>
<body>

<header>
    <h1>Foodie Hub</h1>
</header>

<nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="administration.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<div class="banner">
    <h2>30% Off This Weekend</h2>
    <p>Don't miss out on our special weekend discount! Enjoy delicious meals at unbeatable prices.</p>
</div>

<div class="section-container">
    <div class="card">
        <img src="https://images.unsplash.com/photo-1642026465180-5e25255838e9" alt="Grilled Food">
        <h3>Our New Menu</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse et congue massa, eu fringilla mauris.</p>
        <a href="#">See our new menu</a>
    </div>
    <div class="card">
        <img src="https://images.unsplash.com/photo-1551183053-bf91a1d81141" alt="Salad">
        <h3>Book a table</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse et congue massa, eu fringilla mauris.</p>
        <a href="#">Book your table now</a>
    </div>
    <div class="card">
        <img src="https://images.unsplash.com/photo-1651977560788-98792cd34da0" alt="Chef Cooking">
        <h3>Opening Hours</h3>
        <p>Mon - Fri: 2pm - 10pm<br>Sat: 2pm - 11pm<br>Sun: 2pm - 9pm</p>
    </div>
</div>

<footer>
    <br>
    Designed and Developed by <a href="#">Deepak S</a>
    <p>&copy; 2025 Deepak.All Rights Reserved.</p>
</footer>

</body>
</html>


menu.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Little Lemon - Menu</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

<header>
    <h1>Little Lemon</h1>
</header>

<nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="administration.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<div class="banner">
    <h2>Our Menu</h2>
    <p>Explore our delightful range of dishes crafted for every taste!</p>
</div>

<div class="section-container">
    <div class="card">
        <img src="https://plus.unsplash.com/premium_photo-1661310019346-4cb563a19aec" alt="Grilled Food">
        <h3>Grilled Dishes</h3>
        <p>Try our mouth-watering grilled specials, packed with flavor!</p>
    </div>
    <div class="card">
        <img src="https://images.unsplash.com/photo-1738486511470-471be341a1e3" alt="Salad">
        <h3>Fresh Salads</h3>
        <p>Healthy, fresh, and satisfying salads for all tastes.</p>
    </div>
    <!-- Added Dishes -->
    <div class="card">
        <img src="https://plus.unsplash.com/premium_photo-1705947846996-2887733378a3" alt="Pasta">
        <h3>Delicious Pasta</h3>
        <p>Our pasta dishes are made fresh, with savory sauces and ingredients.</p>
    </div>
    <div class="card">
        <img src="https://plus.unsplash.com/premium_photo-1661387558893-63d24776cf38" alt="Burger">
        <h3>Juicy Burgers</h3>
        <p>Try our juicy, hearty burgers, grilled to perfection with a variety of toppings.</p>
    </div>
    <div class="card">
        <img src="https://plus.unsplash.com/premium_photo-1733306588881-0411931d4fed" alt="Pizza">
        <h3>Classic Pizza</h3>
        <p>Delicious wood-fired pizzas with a crispy crust and fresh toppings.</p>
    </div>
</div>

<footer>
    <br>
    Designed and Developed by <a href="#">Deepak S</a>
    <p>&copy; 2025 Deepak.All Rights Reserved.</p>
</footer>

</body>
</html>


adminstration.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Little Lemon - Administration</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

<header>
    <h1>Foodie Hub</h1>
</header>

<nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="administration.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<div class="banner">
    <h2>Administration Page</h2>
    <p>This page is for administrative tasks, staff management, and other administrative duties.</p>
</div>
<div class="section-container">
    <div class="card">
        <img src="https://www.finedininglovers.com/sites/default/files/styles/1_1_920x920/public/2025-04/20240504-pbc5976.jpg.webp?itok=Ojn7f5Mj" alt="img">
        <h3>FARID AZARANG</h3>
        <p>Farid Azarang is the head pastry chef and co-founder of Artelice Pâtisserie a celebrated French-inspired bakery with locations in Los Angeles.</p>
    </div>
    <div class="card">
        <img src="https://www.finedininglovers.com/sites/default/files/styles/1_1_920x920/public/2025-04/60da8ab5-41c0-4293-bc67-e9cef71a2b6c.JPG.webp?itok=FQzoawDv" alt="Salad">
        <h3>CAT CORA</h3>
        <P>Cat Cora is a Chilean chef and co-owner of Michelin-starred NUB in Tenerife. Trained in Chile, Spain, and France, she also serves as a judge on MasterChef Chile.</P>
    </div>
    <div class="card">
        <img src="https://www.finedininglovers.com/sites/default/files/styles/1_1_920x920/public/2025-03/chef-aitor-zabala-jill-paider.jpg.webp?itok=kazPOI6C" alt="Pasta">
        <h3>GUY FIERI</h3>
        <P>Chef Guy Fieri is the executive chef of Musaafer in Houston, where he crafts Ayurvedic-inspired Indian cuisine. In 2024, Musaafer became Texas’s first Michelin-starred Indian restaurant.</P>
    </div>
    <div class="card">
        <img src="https://www.finedininglovers.com/sites/default/files/styles/1_1_920x920/public/2025-03/tracy-headshot_credit-carter-hiyama.jpg.webp?itok=rYOGJYSn" alt="Burger">
        <h3>TRACY </h3>
        <p>The Texas-based chef behind Birdie’s is known for her elegant, seasonal cooking and commitment to sustainability.</p>
    </div>
    <div class="card">
        <img src="https://www.finedininglovers.com/sites/default/files/styles/1_1_920x920/public/2024-10/DanielGarwood_LuciaBellEpstein.jpg.webp?itok=3_nzm55C" alt="Pizza">
        <h3>DANIEL GARWOOD</h3>
        <p>Australian-born chef Daniel Garwood is the Executive Chef and Partner at ACRU in New York City, where he draws on his global culinary experiences to create a tasting menu that reflects his passion for foraging, seasonality, and sustainable practices.</p>
    </div>
</div>
<footer>
    <br>
    Designed and Developed by <a href="#">Deepak S</a>
    <p>&copy; 2025 Deepak.All Rights Reserved.</p>
</footer>

</body>
</html>


contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Little Lemon - Contact Us</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

<header>
    <h1>Foodie Hub</h1>
</header>

<nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="administration.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<div class="banner">
    <h2>Contact Us</h2>
    <p>Have any questions? Get in touch with us!</p>
</div>

<div class="section-container">
    <div class="card">
        <h3>Email Us</h3>
        <p>Send us an email at <a href="mailto:info@foodiehub.com">info@foodiehub.com</a></p>
    </div>
    <div class="card">
        <h3>Call Us</h3>
        <p>Call us at +123 456 7890 for any inquiries.</p>
    </div>
    <div class="card">
        <h3>Visit Us</h3>
        <p>We are located at 123 Lemon Street, Fruit City.</p>
    </div>
</div>

<footer>
    <br>
    Designed and Developed by <a href="#">Deepak S</a>
    <p>&copy; 2025 Deepak.All Rights Reserved.</p>
</footer>

</body>
</html>


styles.css


html, body {
    height: 100%;
    margin: 0;
}

body {
    font-family: Arial, sans-serif;
    background-color: #9a9a9a;
    display: flex;
    flex-direction: column;
    min-height: 100vh; /* Ensure the body takes full height */
}


footer {
    background-color: #333;
    color: #ccc;
    text-align: center;
    padding: 5px;
    font-size: 0.9em;
    margin-top: auto; 
}

/* Footer link styling */
footer a {
    color: rgb(208, 255, 0);
    text-decoration: none;
    font-weight: bold;
}


nav {
    background-color: #333;
    padding: 10px;
    text-align: center;
}

nav a {
    color: white;
    margin: 0 20px;
    text-decoration: none;
    font-weight: bold;
}

header {
    text-align: center;
    padding: 20px;
}

header img {
    width: 50px;
}

header h1 {
    display: inline-block;
    margin: 0;
    font-size: 2em;
    vertical-align: middle;
}

.banner {
    background-image: url('https://plus.unsplash.com/premium_photo-1661883237884-263e8de8869b');
    background-size: cover;
    background-position: center;
    color: white;
    padding: 80px 20px;
    text-align: center;
}

.banner h2 {
    font-size: 2em;
    margin-bottom: 10px;
}

.section-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
    margin: 40px 20px;
}

.card {
    background: white;
    border-radius: 10px;
    padding: 20px;
    width: 300px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    text-align: center;
}

.card img {
    width: 100%;
    border-radius: 10px;
    height: 200px;
    object-fit: cover;
}

.card h3 {
    margin-top: 15px;
    color: #333;
}

.card p {
    font-size: 0.9em;
    color: #666;
    margin: 10px 0;
}

.card a {
    color: blue;
    text-decoration: underline;
    font-size: 0.9em;
}

.home-section,
.menu-section,
.admin-section,
.contact-section {
    background-position: center;
    background-size: cover;
    color: #fff;
    text-align: center;
    display: flex;
    flex-direction: column;
    justify-content: center;
    min-height: 80vh;
    padding: 50px 20px;
}

.menu-section-container {
    background-image: url('https://plus.unsplash.com/premium_photo-1661883237884-263e8de8869b');
}

.admin-section {
    background-image: url('https://plus.unsplash.com/premium_photo-1661883237884-263e8de8869b');
}

.contact-section {
    background-image: url('https://plus.unsplash.com/premium_photo-1661883237884-263e8de8869b');
}


```
## OUTPUT:
![image](https://github.com/user-attachments/assets/c3a99f16-1d21-4334-9a74-12e049a68d0e)
![image](https://github.com/user-attachments/assets/793a55d3-9a91-4517-87a9-760499faa5c1)
![image](https://github.com/user-attachments/assets/a582c012-96eb-47c1-843d-2d748a03d6d5)
![image](https://github.com/user-attachments/assets/18845dd8-c50e-4959-b254-db00ef3d2da5)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
